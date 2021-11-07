# Master Thesis; Jorge Casinos Buj
## Price innovation and industrial dynamics. A computational model of two sectors..

### Máster en Economía, Universidad de Zaragoza,  2017 -2018
### Directors: Isabel Almudí y Francisco Fatás

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


### Repository content:


This repository contains the Python codes as well as the results of the simulations presented in the master thesis. The repository is organised in the following folders:

#### Simulation Data: 
The simulation data can be downloaded from this [link](https://drive.google.com/drive/folders/1vlIxDurlRA9VzlUvJooVt30m-960fuEK?usp=sharing). The files contained (note that scenario can be base, markI or markII):

   - escernario.xlsx &rarr; Average time series S1 and S2. 
   - escenarioS1.xlsx &rarr; Time series S1 of the 500 simulations
   - escenarioS2.xlsx &rarr; Time series S2 out of 500 simulations
   
#### Jupyter Notebooks / Code

It contains the code in [Jupyter Notebook](http://jupyter.org) ormat needed to replicate all the results. The notebooks can be opened and consulted without having Python installed. However, to run them you will need to install a Python [distribution](https://www.anaconda.com/download/#macos)

  - 01. [MODEL](https://github.com/jcasinos/TFM/blob/master/Jupyter%20Notebooks/Modelo.ipynb) &rarr; computation of the model that faithfully reproduces the pseudocode
  - 02. [SIMULATION](https://github.com/jcasinos/TFM/blob/master/Jupyter%20Notebooks/Simulación.ipynb) &rarr; ccode with which you can replicate your simulations or new ones.
  - 03. [ANALISIS](https://github.com/jcasinos/TFM/blob/master/Jupyter%20Notebooks/Analisis.ipynb) &rarr; code to compute the graphs and descriptive statistics
  
