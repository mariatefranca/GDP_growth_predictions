# What is this for?

This project was built during the Indicium's Lighthouse Program.

"In most years since 1980, global GDP growth has been relatively consistent, generally fluctuating between two and five percent growth from year to year. The most notable exceptions to this were during the Great Recession in 2009, and again in 2020 during the Covid-19 pandemic, where the global economy actually shrank in both of these years. As the world economy continues to deal with the economic impact of the pandemic, as well as the fallout from Russia's invasion of Ukraine in 2022, the future remains uncertain, however current estimates suggest that annual growth will return to steady figures of around 3 percent in 2028."

Aaron O'Neill, May 10, 2023

This project aimed to evaluate the development of an EDA (exploratory data analysis), the knowledge/insights related to a time series, and predict the growth of the GDP index of each country in the years 2024-2028.   
 A comparison with values predicted by Statistica were made.

## Predictions

_modelThe predictions can be acessed in the file ``GDP_growth_mtf.csv`` in the path [data/07_model_output](https://github.com/mariatefranca/GDP_growth_predictions/tree/main/data/07_model_output).

Due to the file size and type of some graphs(Plotly), it was not possible to render the desafio_ds_mtf.ipynb notebook on github. But, its rendering can be viewed at: [https://nbviewer.org/github/mariatefranca/GDP_growth_predictions/blob/main/notebooks/desafio_ds_mtf.ipynb](https://nbviewer.org/github/mariatefranca/GDP_growth_predictions/blob/main/notebooks/desafio_ds_mtf.ipynb)

## Instructions

To run this project locally, in the shell ofLinux chose a folder to clone this repository and execute the following command:

``git clone git@github.com:mariatefranca/GDP_growth_predictions.git``

Create a virtual environment:

``python3 -m venv .env``

Activate the virtual environment:

``source .env/bin/activate``

Install the package used in this project:

``pip install -r src/requirements.txt``



