# TFG Informatica
Este repositorio tiene un trabajo sobre prediccion de valores bursátiles mediante una red recuerrente LSTM, GRU y SimpleRNN.
Trabajo hecho en el 2020.

El trabajo se basas en la descarga de datos de forma gratuita de la bolsa de valores NASDAQ con la API de Quandl y su predicción usando medias móviles y osciladores.

#### Partes
Tiene 3 partes, el trabajo fin de grado por una parte, donde se realiza un estudio de diferentes secuencias y diferentes redes neuronales con celdas diferentes para 6 activos diferentes, AAPL, GOOGL, ATVI, SNRC, MINI, BBOX.

Otra parte es una demo, de donde sale el trabajo fin de grado, se presenta un .csv, con diferentes empresas con una simulación y predicción buena, se recogen los datos y se permite la simulación de una red neuronal con un solo activo, con su correspondiente predicción y con una simulación de inversión en bolsa.

La ultima parte es la versión extendida de ese mismo script, en vez dar un .csv con solo un conjunto de empresas, se ofrece toda la cantidad de empresas que se ofrecen de forma gratuita en la API de Quandl de la bolsa de valores NASDAQ, que cumplan requisitos de las fechas expuestas. Eligiendo un valor k que será el conjunto de empresas a usar.