
<h1 align='center'>
 <b>PROYECTO INDIVIDUAL Nº2</b>
</h1>
 
# <h1 align="center">**`Accidentes Aereos`**</h1>

¡Bienvenidos a mi segundo proyecto individual!
<p align='center'>
<img src="https://slack-imgs.com/?c=1&o1=ro&url=https%3A%2F%2Fcdn.pixabay.com%2Fphoto%2F2016%2F09%2F15%2F16%2F13%2Fairplane-1671967_1280.jpg"  height=300>
<p>

### **Objetivo**
En este proyecto soy una Data Analytics y se me propone analizar los accidentes aéreos. La **Organización de Aviación Civil Internacional (OACI)**, organismo de la Organización de las Naciones Unidas, quiere investigar en profundidad los accidentes producidos desde inicios del siglo XX. Para ello, el objetivo principal es poder obtener un análisis de datos relacionado a esto, junto a un dashboard que complemente los análisis con sus visualizaciones. 

Para realizar estos análisis utilicé el dataset llamado "AccidentesAViones.csv".

`ETL`
Primero comencé por descargar el dataset y lo revisé para evaluar su contenido. Verifiqué cómo estaba separado y cuantas columnas tenía.
Allí me encontré con varios incovenientes: filas vacías, algunos títulos en mayúscula, otros en minúscula y otros mezclados, titulos separados con guiones y otros sin. También detecté títulos en español y en ingles.
Por lo que separé primero las columnas por un mismo caracter, la coma. Luego definí un mismo criterio para los títulos e idioma. Eliminé las filas vacías. Separé por columnas y verifiqué su contenido. Eliminé las columnas que eran irrelevantes o que estaban incompletas, ya que no me servían para comenzar mi análisis. Luego agregué las columnas necesarias, y separé por ejemplo la columna "Ruta" en "Country" y "City" y agregué la columna "Year" y "Month". Definí los criterios para que todas las columnas estuvieran completas. Posteriormente hice la revisión para corroborar que las columnas que me quedaron contengan información completa y relevante y tengan los formatos adecuados para poder hacer cruce de datos y análisis de los mismos.
Guardé los cambios en el dataset.

Una vez ya con los datos listos y limpios, comencé con el análisis EDA.

`EDA` 
Con los datos ya listos comencé mi analisis. 
Este Dataset contiene información sobre accidentes de aviación con 4990 entradas y 10 columnas que incluyen información sobre la ruta, operador, tipo de aeronave, número total de personas a bordo, número de fallecidos, resumen del incidente, año, mes, ciudad y país. Los tipos de datos predominantes son objetos (strings) para las columnas que contienen texto y enteros de 32 bits para las columnas numéricas.
En los diferentes "Markdown" están registradas las conclusiones de cada análisis realizado.

Conclusiones: 
- Los años con más muertes en accidentes aéreos fueron entre los años 1950 y 2000.
A partir de principios de la década de 2000, la frecuencia de accidentes comenzó a disminuir y se mantuvo relativamente baja en la década de 2010. La década de 2020 muestra una frecuencia similar a la de principios del siglo XX.

- En las décadas de mayores muertes se dieron la mayor cantidad de sobrevivientes. Se puede ver que a partir del año 2000 en adelante hay un leve incremento de sobrevievientes en accidentes aéreos.

- El 40% de los tipos de aeronaves y de operadores con más accidentes son militares o de fuerzas armadas.

- Rusia es el país con más accidentes aéreos.

- No suelen haber muertes mayores a 300/400 personas en accidentes aéreos, los casos que hubieron son aislados.

- En la última década han disminuido los accidentes y con ello las muertes de tripulantes. Lo que si, aún quedan por tomar muchas más medidas preventivas, correctivas y oportunidades de mejora para reforzar y conseguir disminuir la tasa de fatalidad de accidentes propiamente dicho.


`Dashboard`
Se adjunta captura del dashboard realizado para presentar los resultados del proyecto y compartir el cumplimiento de los KPI´s propuestos y conclusiones.


`KPIs`
Se realiza la evaluación de los KPI´s propuestos:
 - KPI 1: Evaluar la disminución de un 10% la tasa de fatalidad de la tripulación en los últimos 10 años, comparado a la década anterior. 
El resultado de la tasa de fatalidad de la tripulación muestra que no se cumplió el objetivo de reducir esta tasa en un 10% o más durante el período de 2011 a 2021. En cambio, se observa un aumento en la tasa de fatalidad de la tripulación en ese período, lo que indica una tendencia preocupante.
Dado que la tasa de fatalidad de la tripulación ha aumentado en lugar de disminuir, es esencial que se realice una revisión exhaustiva de las políticas, procedimientos y medidas de seguridad operacional. Se deben identificar y abordar las posibles causas de este aumento en la tasa de fatalidad de la tripulación.

Es crucial que se implementen medidas preventivas y correctivas efectivas para garantizar la seguridad de la tripulación en futuras operaciones aéreas, y buscar oportunidades de mejora. La seguridad de la tripulación debe seguir siendo una prioridad en la gestión de la seguridad en la aviación.

 - KPI 2: Evaluar si el Operador que más accidentes tuvo entre los años 2001 y 2021 disminuyo un 15% de accidentes en comparación con la decada del 2001 al 2011. 
El resultado fue positivo, se cumplió ese Kpi.
Se observa que "Military - U.S. Army" experimentó una disminución significativa en la cantidad de accidentes entre los años 2011 y 2021. La disminución en la cantidad de accidentes fue del 66.67%, lo que supera el umbral del 15% establecido como referencia para una disminución significativa.El análisis de este KPI muestra que este operador tuvo la mayor cantidad de accidentes en el período de 2001 a 2021. Sin embargo, durante la última década (2011-2021), el operador ha logrado una reducción sustancial en la cantidad de accidentes, superando el umbral del 15% de disminución.
Esta disminución en la cantidad de accidentes indica un esfuerzo positivo por parte de "Military - U.S. Army" en la mejora de su seguridad operacional y puede considerarse como un logro importante en la gestión de la seguridad de sus operaciones aéreas.

## Fuente de datos:

- Dataset principal, incluido en el repositorio del proyecto.

## Herramientas y tecnología utilizadas:
Durante el desarrollo de este proyecto de análisis exploratorio de datos y visualización, se utilizaron las siguientes herramientas y tecnologías:

- Python: Se empleó el lenguaje de programación Python para realizar el análisis de datos, manipulación de los conjuntos de datos y generación de gráficos. Se utilizaron bibliotecas como Pandas, Seaborn, NumPy y Matplotlib para llevar a cabo estas tareas.

- Power BI: Se utilizó Power BI, una herramienta de visualización de datos de Microsoft, para crear el dashboard interactivo.

- GitHub: Se utilizó este repositorio https://github.com/Silvanaggs15/PI-DA como sistema de control de versiones para el seguimiento de los cambios realizados en el proyecto.

## Estrucutura del repositorio:

El repositorio está organizado de la siguiente manera:

- README.md: Archivo que contiene la descripción del proyecto, las conclusiones, las visualizaciones y las recomendaciones.

- Datasets: Contiene el dataset "AccidentesAviones.csv" utilizado en el proyecto.

- Dashboard: Contiene el dashboard con la presentación del proyecto en PowerBI y una imagen de la misma.

- Notebooks: "Proyecto_Individual", Compuesto por el ETL: contiene la limpieza de los datos y armado de nuevos dataframes. EDA: contiene el analisis exploratorio de datos, visualizaciones y primeras conclusiones. Kpi´s: contiene la evaluación de los mismos y su análisis.
