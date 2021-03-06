# Trabajo Fin de Máster; Jorge Casinos Buj
## Innovación precios y dinámica industrial. Un modelo computacional de dos sectores.

### Máster en Economía, Universidad de Zaragoza, Curso 2017 -2018
### Directores: Isabel Almudí y Francisco Fatás

<p align="center"> <b> Resumen:</b><br> </p>

El principal objetivo de esta tesina será introducir el estudio de la dinámica industrial desde la perspectiva de la Economía evolutiva empleando modelos computacionales. Para ello se propone un modelo computacional (ABM)
para analizar la co-evolución entre dos sectores. El Sector 1 produce bienes
de capital que son mejorados a través de la innovación. Estos bienes serán
incorporados por el Sector 2 para producir distintas variedades de un bien
de consumo. El modelo incorpora aspectos recientemente desarrollados por
la economía evolutiva como la capacidad de absorción, la percepción de los
competidores o las dinámicas emergentes de precios. El modelo será capaz
de replicar como propiedades emergentes los hechos estilizados de distintos
regímenes tecnológicos.

<p align="center"> <b> Abstract:</b><br> </p>

The main objective of this dissertation is to introduce the approach of Evolutionary Economics to industrial dynamics by using computational models.
We propose a computation model (ABM) to analyze the coevolution between
two sectors. Sector 1 produces capital goods (machines) which are improved
through innovation. These machines are used by Sector 2 to produce varieties
of a consumption good. The model incorporates elements recently developed
by Evolutionary Economics such as absorptive capacity, rivals' perception or
emergent pricing dynamics. The model is able to replicate the stylized facts
of diferent technological regimes as emergent properties.


### Conteidos repositorio:

Este repositorio contiene los códigos de Python así como los resultados de las simulaciones que se presentan en el TFM. El repositorio se organiza en las siguientes carpetas:

#### Datos Simulaciones: 

Los datos de las simulaciones se pueden descargar en este [enlace](https://drive.google.com/drive/folders/1vlIxDurlRA9VzlUvJooVt30m-960fuEK?usp=sharing). Los archivos contenidos (tener en cuenta que escenario puede ser base, markI o markII):

   - escernario.xlsx &rarr; Series temporales medias S1 y S2 
   - escenarioS1.xlsx &rarr; Series temporales S1 de las 500 simulaciones
   - escenarioS2.xlsx &rarr; Series temporales S2 de las 500 simulaciones
   
#### Jupyter Notebooks / Código

Contiene el código en formato [Jupyter Notebook](http://jupyter.org) necesario para replicar todos los resultados. Las libretas pueden abrirse y consultarse sin necesidad de tener Python instalado. Sin embargo para ejecutarlas será necesario instalar una [distribución](https://www.anaconda.com/download/#macos) de Python

  - 01. [MODELO](https://github.com/jcasinos/TFM/blob/master/Jupyter%20Notebooks/Modelo.ipynb) &rarr; computación del modelo que reproduce fielmente el pseudocódigo
  - 02. [SIMULACIÓN](https://github.com/jcasinos/TFM/blob/master/Jupyter%20Notebooks/Simulación.ipynb) &rarr; código con el que se pueden replicar las simulaciones realizadas u otras nuevas
  - 03. [ANALISIS](https://github.com/jcasinos/TFM/blob/master/Jupyter%20Notebooks/Analisis.ipynb) &rarr; código para elaborar los gráficos y los estadísticos descriptivos
  
