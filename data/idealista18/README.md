# Introducción

Este conjunto de datos es una adaptación de los datos en formato RData del paquete de datos idealista18 usado para la investigación en modelos hedónicos del precio de la vivienda y modelos de econometría espacial. Estos trabajos están principalmente orientados al estudio de las relaciones de la ubicación con el precio de la vivienda y la distribución espacial de los mercados de la vivienda (submercados de la vivienda desde el sentido espacial de término).

# Referencias

Referencia al proyecto original: https://github.com/paezha/idealista18
Paper Data In Brief preliminar que describe la estructura de la información: https://github.com/paezha/idealista18/blob/master/data-in-brief/dib-idealista18.pdf

# Documentación

En la subcarpeta *data* de este proyecto se pueden localizar los distintos ficheros en formato csv comprimido. Dentro de esta carpeta se distribuyen los datos en:

* **assets**: anuncios de venta en 3 ciudades principales de España
* **polygons**: división espacial en zonas de las 3 ciudades principales
* **POIs**: puntos de interés en las 3 ciudades (estos puntos de interés son elementos principales de estas ciudades no puntos de interés al uso)
* **OSM**: Puntos de interés de OpenStreetMaps
* **INE**: secciones censales de ine y sus datos del censo de población y viviendas desarrollado en 2011. El código de sección censal es una cadena de longitud 10 caracteres compuesta por números cuyo nombre es *CUSEC*. 

En los datos de INE tendremos dos ficheros:

* *ine/ine-census-2011-#CLEAN_CITYNAME#.csv.gz* -> datos del censo de población y viviendas (https://www.ine.es/censos2011_datos/indicadores_seccen_rejilla.xls) [diccionario de datos]
* *ine/ine-censal-polygon-boundaries-2011-#CLEAN_CITYNAME#.csv.gz* -> Polígonos del datos del censo de poblacion y viviendas (https://www.ine.es/censos2011_datos/cen11_datos_resultados_seccen.htm) [Fuente: ine]


# Términos de uso

El uso de este conjunto de datos está sujeto a la licencia indicada https://github.com/paezha/idealista18/blob/master/LICENSE.md
