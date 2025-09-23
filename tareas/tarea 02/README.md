# Tarea 2 Intro a Ciencias de datos

En esta tarea se debe de hacer un analisis de los datos de ebird, como se ve en el jupyter

## Explicacion de la Extraccion de datos -->

como se ve en la tarea se hizo la extraccion de datos por un ciclo for , esto tal que, por lo leido en la api, no hay otra forma de descargar los datos de forma masiva
esta no es la forma mas eficiente de hacerlo , puesto que el iterar hace que tome tiempo en lo que llega la señal del request, ademas de, ser una carga para el propio servidor
ademas, toda la informacion se decidio dejar en la misma ruta que el archivo jupyter para hacer mas comodo el proceso de hacer la tarea

## trasformacion de dataframe pandas a geodataframe
La fuente que se consulto para saber como hacerlo es la pagina [https://geopandas.org/en/stable/gallery/create_geopandas_from_pandas.html] , de la cual, en al transformacion se copio gran apartado del codigo en la seccion 
"Creating a GeoDataFrame from a DataFrame with coordinates"
tambien se leyo [https://geopandas.org/en/stable/docs/user_guide/io.html] aunque no se uso como tal para copiar parte de codigo si no para aprender de mejor manera


## Creacion de graficos pandas -->
Para la creacion de los graficos en pandas se leyo la documentacion oficial -->
[https://pandas.pydata.org/pandas-docs/stable/user_guide/visualization.html]
[https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.plot.html]
si bien no se copio como tal el codigo si hay una fuerte inspiracion de ambos , por ende se cita aqui