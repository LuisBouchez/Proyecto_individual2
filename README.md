
# PROYECTO INDIVIDUAL N°1 - DATA ENGINEER

Rol a desarollar : 
- Data Analitys

- El proyecto se enfoca en el análisis de accidentes aéreos y tiene como objetivo principal comprender y analizar la problemática asociada a estos eventos. Los accidentes aéreos representan una preocupación en la industria de la aviación y la seguridad de los pasajeros y la tripulación es una prioridad. Mediante el estudio de los datos disponibles, se busca identificar patrones, factores de riesgo y posibles mejoras en los protocolos de seguridad. El análisis de estos accidentes permitirá obtener información valiosa para tomar medidas preventivas y reducir la tasa de incidentes en el futuro. En este readme se proporcionará una visión general del proyecto, las bases de datos utilizadas y los objetivos que se pretenden alcanzar.


## Análisis exploratorio de los datos

1.-Carga de datos: Se cargó el conjunto de datos que contiene información sobre accidentes aéreos. Las columnas incluidas son: fecha, hora declarada, ruta, operador, número de vuelo, tipo de aeronave, registro, número de serie, personas a bordo, pasajeros a bordo, tripulación a bordo, cantidad de fallecidos, fallecidos entre pasajeros, fallecidos entre la tripulación y fallecidos en tierra, y un resumen del accidente.

2.-Análisis y limpieza de datos:

Se realizó un análisis inicial de los tipos de datos de las columnas y se identificó que la columna "fecha" estaba en formato de texto en lugar de fecha.
Se convirtió la columna "fecha" al formato de fecha adecuado utilizando la función de conversión de fecha en Python.
Se identificaron y manejaron los valores nulos o faltantes en las columnas relevantes, como la cantidad de fallecidos y pasajeros a bordo.
Análisis exploratorio de datos:

3.-Se realizaron análisis descriptivos de las variables relevantes, como el número de accidentes agrupados por año.
Se agruparon los datos por año y se contaron los accidentes en cada año para obtener una visión general de la distribución de accidentes aéreos a lo largo del tiempo.
Se identificaron los 10 años con el mayor número de accidentes para un análisis más detallado.
Visualización de datos:

4.-Se utilizaron gráficos y visualizaciones, como histogramas y gráficos de líneas, para representar la distribución de accidentes aéreos por año y la evolución de los porcentajes de supervivencia a lo largo del tiempo.
Se utilizaron técnicas de filtrado y ordenamiento para mostrar solo las 10 aeronaves más comunes y su frecuencia de accidentes.
En resumen, el proceso de EDA incluyó la carga y limpieza de datos, análisis exploratorio de variables relevantes, visualización de datos y extracción de información clave sobre accidentes aéreos, tendencias a lo largo del tiempo y distribución por tipo de aeronave. Este análisis proporcionó información valiosa para comprender mejor los datos y tomar decisiones informadas en el proyecto.
## Instalacion
Para el siguiente proyecto se usaron las siguietes tecnologias y librerias:

-Python

-Pandas

-Numpy

-Matplotlib

-Power BI

-Visual studio code

    