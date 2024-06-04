# TP-N3-Max-min-avg-etc

Listar todos los autores de que sean de Nacionalidad Argentina
```
SELECT * FROM Autores WHERE Nacionalidad = 'Argentino';
```
Listar todos los autores que tengan hayan publicado entre 1960 a 1980.
```
SELECT * FROM Autores WHERE AnoPublicacion BETWEEN 1960 AND 1980;
```
Mostrar el promedio de la edad de publicación. (avg).
```
SELECT AVG(EdadPublicacion) FROM Autores;
```

