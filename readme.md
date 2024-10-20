# Proyecto Videoclub - Gestión de Películas y Alquileres
---

Este proyecto se enfoca en la creación de un esquema para gestionar un sistema de videoclub, incluyendo la gestión de películas, copias de películas, socios, direcciones, géneros, directores y alquileres.

## Esquema y Tablas
---
El esquema del proyecto se denomina `rponce_videoclub` y contiene las siguientes tablas:

- **socios**: Información de los socios del videoclub.
- **direcciones**: Almacena las direcciones de los socios.
- **generos**: Categorías de películas.
- **directores**: Información de los directores de las películas.
- **peliculas**: Detalles de las películas, incluyendo su género y director.
- **copias_pelicula**: Almacena las copias físicas de las películas disponibles en el videoclub.
- **alquiler**: Registra los alquileres realizados por los socios.
- **tmp_videoclub**: Tabla temporal para importar y procesar los datos antes de insertarlos en las tablas finales.

## CONDICIONES DEL PROYECTO

Esta práctica se entregará en dos partes :
- Diagrama Entidad/Relación en formato draw.io
- Script SQL que debe crear un nuevo esquema, crear todas las tablas, cargar datos y las
dos consultas que se piden (aunque el script solo mostrará la última, deben ir las dos).

     -  Se debe aplicar **normalización** siempre que se pueda.
     -  #   G E S T I O N _ V I D E O C L U B - M O D E L A D O _ D A T O S _ S Q L  
 #   G E S T I O N _ V I D E O C L U B - M O D E L A D O _ D A T O S _ S Q L  
 