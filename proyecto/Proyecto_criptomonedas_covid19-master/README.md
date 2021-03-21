# Proyecto_criptomonedas_covid19

  Este repositorio está enfocado a contener el trabajo realizado como proyecto para la asignatura TEL - 354, Minería de Datos.
El objetivo de este proyecto es realizar un análisis que permita concluir la incidencia de la pandemia producida por COVID-19
en los valores de las criptomonedas más relevantes del mercado mundial, específicamente BitCoin y Ethereum.
  
  Se tienen 3 datasets, dos referentes a las criptomonedas que tienen por nombre BTC.xlsx y ETH.xlsx, y el dataset referente a
la información del COVID-19 que tiene por nombre dataset_covid.

Las columnas de dataset_covid son:

* dateRep : Conjunción de la fecha completa. (date)
* day : Dia. (int)
* month : Mes. (int)
* year  : Año. (int)
* cases : Cantidad de casos.  (int)
* deaths : Cantidad de muertes. (int)
* countriesAndTerritories: Nombre del país en cuestión. (string)
* geoId :  Código que representa a una entidad geográfica. (string)
* countryterritoryCode: Código correspondiente al país. (string)
* opData2019
* continentExp
* Cumulative_number_for_14_days_of_COVID-19_cases_per_100000
   
Las columnas de los datasets de criptomonedas son:

* Date : Fecha de la jornada. (date)
* Open : Valor que obtuvo la criptomoneda al abrir la jornada. (float)
* High : Valor máximo que obtuvo la criptomoneda al finalizar la jornada. (float)
* Low  : Valor mínimo que obtuvo la criptomoneda al finalizar la jornada. (float)
* Close : Valor con el que la moneda cerró la jornada.  (float)
* Volume : Número total de monedas negociadas en un valor durante la jornada. (int)
* Market Cap : Valor total en dolares de la totalidad de las criptomonedas. (int)
