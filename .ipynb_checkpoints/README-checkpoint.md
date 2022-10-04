# Swissgrid-Redispatch
Analysis of redispatch measures for the swiss power grid.

## About
The data set are the redispatch measurements taken from swissgrid to keep the power grid stable.

## Motivation
The Energy Crisis is currently raging on in Europe. While all countries suffer from high energy prices, grid operators are not only fighting for enough power, but also need to keep the grid stable --  a daring task. The work is based on a simple open source data and gives a small insight into the workings of keeping the grid stable through redispatches.

For this project I wanted to better understand:
1. How dependant is Europe on Switzerland and vice versa?
2. How often is a redispatch performed? Is it getting worse with the energy crisis? And what plants are used?
3. Will it get worse?

## Requirements

The following installations are required (with the respective dependancies) to run the code:

- python 3.*
- pandas 1.*
- jupyter 
- seaborn 0.12.*

## Description

There are two notebook and a pre-prepared .csv file containing all the nececassry data. 
The notebook redispatch_switzerland.ipynb contains all the analysis and commentary used for the medium article.
The notebook scrape.ipynb contains the code to download all the .csv files and merge them together to get the dataset. The data is available in the swissgrid.ch homepage, free to download.


## Results

All the non-technical results can be found [here](https://medium.com/@alexander.wieland.aw/why-switzerland-is-essential-for-the-european-power-system-51a4a5adeea8).
The technical details are described in the .ipynb



## Licensing, Authors, Acknowledgements
At this point giving credit so [swissgrid](https://www.swissgrid.ch/de/home/customers/topics/redispatch.html) for the excellent work and kindniss of making this data available. No commercial intentions are followed by creating this dataset, 

