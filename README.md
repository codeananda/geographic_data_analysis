# Geographic Data Analysis 🌎

[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

A paid data analysis project I completed on Upwork. It was a long-term tutoring project where I taught the client intermediate python data analysis by showing them what to do. We used eseential libraries such as pandas, numpy, matplotlib and seaborn among others. 

![tasmax_max_temp in South-Central Asia](https://user-images.githubusercontent.com/51246969/131851657-28af39fa-08dd-4451-a2ba-20fb84103286.png)

*An example plot created for the final deliverable. I would have preferred more modern styling but it was for scientific publication.*

It was a two-part project that consisted of weekly, live-coding calls and lead to the following ⭐⭐⭐⭐⭐ reviews:

<img width="651" alt="Screenshot 2021-09-02 at 14 16 12" src="https://user-images.githubusercontent.com/51246969/131841883-3aeb5608-bcb3-477a-865b-3493eb33ef05.png">

<img width="662" alt="Screenshot 2021-09-02 at 14 16 03" src="https://user-images.githubusercontent.com/51246969/131841898-88233c62-55ef-41b3-851a-180383704d27.png">

# Define the Problem

**THE DATASET**

We have temperature data for every 50 km^2 cell on the Earth's surface for the last 100 years and predictions for those cells for the next 100 years. The predictions were generated independently by four different laboratories. 

**THE PROBLEM TO INVESTIGATE**

Analyse how the number and intensity of heatwaves is expected to change in the next 100 years. Compare and contrast the predictions made by each of the laboratories. 

# Noteable Notebooks 📕

* Check out [`4_heatwaves`](https://github.com/theadammurphy/geographic_data_analysis/tree/main/4_heatwaves) to see how I created 300+ pdfs of plots by each cell.

* Check out [`5_final_plots`](https://github.com/theadammurphy/geographic_data_analysis/tree/main/5_final_plots) to see some of the final deliverables for the project - publication-ready plots of tasmin/tasmax data by cell and by region. 

* A good balance of plots and analysis can be found in the [heatwave_analysis.ipynb](https://github.com/theadammurphy/geographic_data_analysis/blob/main/4_heatwaves/heatwave_analysis.ipynb) notebook. 

* The [historical_analysis_tasmax.ipynb](https://github.com/theadammurphy/geographic_data_analysis/blob/main/3_historical/historical_analysis_tasmax.ipynb) notebook explores six different methods to define a heatwave and plots their differences for a sample of cells.

Note: I have not uploaded the data to Github as it is several GBs worth. However, the output of the notebooks is saved, so you can see exactly what I was doing.

# Terminology

The dataset consisted of several excel files containing the min/max temperature for every 50 km^2 (cell) of the Earth for the last 100 years. We combined this with four similar datasets containing predictions of the min/max temperature for every 50 km^2 cell of the Earth for the next 100 years. We restricted our analysis just to points on land.

* *Cell* - a 50 km^2 grid on Earth given by longitude and latitude point.
* *Tas* - Temperature at Surface, this is a particular method geographers and meterologists use to measure the temperature. 
* *Tasmin* - Temperature at Surface (TAS) minimum value for that day. The minimum temperature recorded on that day for that cell.
* *Tasmax* - Temperature at Surface (TAS) maximum value for that day. The maximum temperature recorded on that day for that cell.

# Libraries Used 📚

I used Python and the following libraries:

* Numpy
* Pandas
* Matplotlib
* Seaborn
* Dask
* Xarray

# This Repo is a Work-in-Progress 🏗

I finished this project in August 2020 and have been kept busy with other projects since then. Now, I am in the process of tidying everything up so it can be presented to the world in a nice manner. You are one of the lucky souls who gets to see the repo in its raw form. But this means that not everything is as clean or orderly as it should be.
