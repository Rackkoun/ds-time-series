# Time Series

In this repo we will have a look at time series. Compared to the main branch, there are additional Notebooks and each of the Notebooks has more details. 
Especially in [this Notebook](04_Time_Series_Simulation.ipynb) you can finde a lot of information about ARMA models.

## Task

Please work in pairs through all the notebooks in this particular order:

1. [Intro to EDA with Time Series](01_Intro_EDA_Time_Series.ipynb)
1. [Time Series Stock Price Example](02_Time_Series_Stock_Price.ipynb)
1. [Time Series Moving average animation](03_Time_Series_Moving_Average.ipynb)
1. [Time Series Simulation](04_Time_Series_Simulation.ipynb)
1. [ACF and PACF plots](05_ACF_PACF.ipynb)

## Environment

Use the [requirements](requirements.txt) file in this repo to create a new environment. For this you can either use `make setup` or the following commands:

```BASH
pyenv local 3.9.4
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```