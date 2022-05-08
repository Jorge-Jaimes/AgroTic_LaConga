

<h1 align="center"> Print-Plant </h1> <br>
<p align="center">
  <a href="https://gitpoint.co/">
    <img alt="GitPoint" title="GitPoint" src="https://i.postimg.cc/mgQ89jDb/Printl-Plant.png)](https://postimg.cc/21SQR4hJ" width="450">
  </a>
</p>


## Introducción

El presente proyecto es un código escrito en Python con el cual se presenta la página web “Print-Plant”, en donde se visualiza el post-procesado de datos ambientales, con el fin de ayudar a agricultores en la determinación de la mejor zona y temporada para sembrar sus cultivos; este análisis se realizó a partir de datos obtenidos de estaciones meteorológicas EVAs.

## Características

* Análisis de datos
* Interacciona con la pagina web "Print-plant"

### Libreias usadas 

* Pandas
* NumPy
* Matplotlib
* Seaborn
* APIMakeSens

### FRAMEWORK: Streamlit

## Archivos

* DeviceTransform.ipynb

En este código se ordenan, clasifican y depuran los datos, con el fin de obtener datafremes lo más limpios y óptimos para un posterior análisis  sencillos y confiable.

* Master.ipynb

En éste código se encuentran las funciones con las cuales se discriminan los datos para obtener los rangos de días óptimos, en base a la temperatura, húmeda y presión a las cuales cada cultivo es sensible.

* App.py

El código al cual se le inyecta el dataframe de los resultados obtenidos en el análisis de datos genera una pagina web con una interfaz gráfica donde se presenta los resultados obtenidos a través de una visualización amigable al usuario.

## Autores

Jorge  Jaimes

Kevin Dlaikan

Luigui Miranda
