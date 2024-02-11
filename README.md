
<h1>Práctica de Base de Datos SQL</h1>

Este repositorio contiene el código SQL para la práctica de diseño y manipulación de una base de datos relacionales. La práctica se enfoca en el diseño de un esquema de base de datos para un videoclub, que incluye tablas para socios, películas, préstamos, entre otras.

<h2>Estructura de la Base de Datos</h2>

La base de datos está organizada en las siguientes tablas:

Socio: Almacena la información de los socios del videoclub, incluyendo su nombre, apellidos, fecha de nacimiento, teléfono y número de identificación.
Direccion: Guarda las direcciones de los socios, asociadas mediante su ID.
Pelicula: Contiene detalles sobre las películas disponibles en el videoclub, como el título, año de publicación, género, director y sinopsis.
Copia_Pelicula: Registra las copias de las películas disponibles para préstamo, identificadas por un ID único.
Prestamo: Registra los préstamos realizados por los socios, incluyendo el ID de la copia prestada, el ID del socio, la fecha de préstamo y la fecha de devolución (si está disponible).
