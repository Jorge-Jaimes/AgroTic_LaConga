# AgroTic_LaConga


## Introducción

El presente proyecto esta es un código escrito en Python con el cual se presenta la pagina web “Print-Plant”, en donde se visualizan el pos proseado  de datos ambientales, con el fin de ayudar a agricultores en la determinación de la mejor zona y temporada para sembrar sus cultivos, esto se hizo aparir de datos obtenidos de estaciones meteorológicas EVAs.

## Características

* Análisis de datos
* Interacciona con la pagina web

### Libreias usadas 

* Pandas
* NumPy
* Matplotlib
* Seaborn
* APIMakeSens

### FRAMEWORK: Streamlit

## Archivos

* DeviceTransform.ipynb

En este código se ordena, clasificación  y  depuran los datos, con el fin de obtener datafremes lo mas limpios y óptimos para un posterior análisis  sencillos y confiable.

* Master.ipynb

En este código se encuentran las funciones con las cuales se discriminan los datos para  obtener los rangos de días optimos, en base a la temperatura, húmeda y presión a las cuales cada cultivo es sensible.

* App.py

El código al cual se le inyectan el dataframe de los resultados obtenidos en el análisis de datos, este código genera una pagina web en donde se presenta una visualización amigable al usuario de los resultados obtenidos

##Autores 
Jorge  Jaimes
Kevin Dlaikan   
Luigui Miranda
