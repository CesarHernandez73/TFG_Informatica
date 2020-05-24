# TFG Informatica
Este repositorio tiene un trabajo sobre prediccion de valores bursátiles mediante una red recuerrente LSTM.
Trabajo hecho en el 2020.

El trabajo se basas en la descarga de datos de forma gratuita del indide NASDAQ con la API de Quandl y su predicción usando medias móviles y osciladores.

#### Partes
Se tienen dos archivos diferentes. La demo donde solo se tienen 11 activos del indice NASDAQ y el script extendido donde se guardan 50 activos del mismo indice, con facil modificación para poder descargar todos. Se toman estos valores en búsqueda de un correccto funcionamiento de la red y del portatil ya que cuantos mas datos se necesita un ordenador mas potente para poderlo correr

Cada script (demo y extendido) tiene su carpeta datos por separado, al descargar los script no hace falta descargarse los datos ya que los descarga directamente el código, pero si que es necesario es crear la carpeta datos en el mismo directorio donde este el script.
