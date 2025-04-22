# 3rd-Repo
SQL Caps, >= 30 duración

Duración de cada capítulo y serie >=30 minutos RIGHT JOIN 
22/04/25
SELECT Series.titulo AS 'Título de la Serie',
       Episodios.titulo AS 'Título del Episodio',
       Episodios.duracion AS 'Duración'
FROM Series
RIGHT JOIN Episodios
ON Series.serie_id = Episodios.serie_id 
WHERE Episodios.duracion >= '30'
