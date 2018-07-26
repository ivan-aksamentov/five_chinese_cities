# Analysis and forecasting of levels of PM<sub>2.5</sub> fine particulate matter pollution in the air of Chinese cities

This repository provides a Python notebook that demonstrates basic exploratory analysis of time-series data as well as a few simple forecasting models, using popular data science packages.


## Goals

 - conduct an explorative data analysis
 - set up prediction model for the "PM2.5" variable for two cities
 - extract 20% from the dataset for evaluation
 - select and implement a suitable error measure
 - compare anomalies and predictions for the two cities


## Data

The dataset used is "PM<sub>2.5</sub> Data of Five Chinese Cities" described in:

    Liang, X., S. Li, S. Zhang, H. Huang, and S. X. Chen (2016), 
    PM2.5 data reliability, consistency, and air quality assessment 
    in five Chinese cities, J. Geophys. Res. Atmos., 121, 
    10,220–10,236, doi: 10.1002/2016JD024877.


## How to

You may run the notebook itself (`five_chinese_cities.ipynb`) or just read an HTML article generated from it (`five_chinese_cities.html`)

Note: paremeter search for SARIMAX model requires significant amount of time and computatonal resources in order to run


## Install and run

Install unrar. For example, on Ubuntu 16.04:

    sudo apt-get install unrar

Install required Python 3 packages listed in `requirements.txt`. For example:

    pip3 install -r requirements.txt

Run Jupyter server and open notebook in default browser:

    jupyter notebook five_chinese_cities.ipynb


## Generating HTML

You may re-generate the HTML from the notebook using `nbconvert` and the template file `my_template.tpl` provided:

    jupyter nbconvert --to html --template=my_template.tpl five_chinese_cities.ipynb

Note that the template depends on jquery library.


## Authors

- [Ivan Aksamentov](https://github.com/ivan-aksamentov)


## License

MIT License (excluding the dataset)
