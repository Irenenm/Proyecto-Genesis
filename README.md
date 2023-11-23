# Proyecto Genesis

Este proyecto muestra el comienzo de mi aprendizaje en el mundo del análisis de datos. Se trata del primer proyecto que llevé a cabo y se realizó durante el Bootcamp de Data Analytics de Adalab para poner en práctica los conocimientos adquiridos durante el primer módulo


## Descripción

En este proyecto partimos de diferentes archivos en los que tenemos la información repartida. Necesitamos obtener una base de datos en la que estos 3 archivos estén integrados y relacionados entre sí.

De esta forma tenemos 3 ficheros diferentes:

- Archivo en formato XML.
- Archivo en formato txt.
- Archivo en formato sql.

Para ello debemos:

- Crear la base de datos, crear las diferentes tablas.
- Limpieza de los datos tanto del archivo xml, txt como sql.
- Creación de funciones genéricas para la limpieza de los datos.
- Insertar de los datos de los ficheros xml, txt y sql en la base de datos.

## Integrantes
- Irene Nicolás
- Verónica Marina
- Andrea Cabrera
- Griselle Alanís

## Motivación de la realización del proyecto

Creación de una BBDD cuyas tablas estén conectadas mediante claves primarias y foráneas.

## Estructura de las carpetas que tiene el proyecto

Este repositorio se estructura en 2 carpetas y una imagen en la que se puede observar la base de datos finalizada.
Carpetas: 

- carpeta 'datos':  el archivo 'data_sql.sql' contiene la información que insertaremos en la tabla 'tabla_sql' ya con la limpieza aplicada. El archivo 'data_txt.txt' contiene la información que insertaremos en la tabla 'tabla_txt'. Por último, el archivo 'data_xml.xml' contiene la información que insertaremos en la tabla 'tabla_xml'.
 
- carpeta 'jupyters':  el archivo 'SQL_creacion_BBDD.ipynb' contiene el código necesario para la creación de la base datos y las tablas que la componen. El archivo 'txt_limpio.ipynb' contiene el código necesario para la limpieza del archivo 'data_txt.txt' y su posterior inserción en la base de datos. Por último, el archivo 'xml_limpio.ipynb' contiene el código necesario para la limpieza del archivo 'data_xml.xml' y su posterior inserción en la base de datos. 

## Lenguajes utilizados

- Python
- SQL

## Librerías utilizadas

 * **mysql.connector**. Puedes encontrar la documentación oficial a través del siguiente [link](https://dev.mysql.com/doc/connector-python/en/connector-python-examples.html).

 * **xml.etree.ElementTree**. Puedes encontrar la documentación oficial a través del siguiente [link](https://docs.python.org/es/3/library/xml.etree.elementtree.html).