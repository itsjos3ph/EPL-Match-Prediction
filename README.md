# Project Overview

In this project, I predict the winner of football matches in the English Premier League (EPL) from statistics in taken from 2022.  

**Project Steps Taken**

* Scrape match data using requests, BeautifulSoup, and pandas.  
* Clean the data and get it ready for machine learning using pandas.
* Make predictions about who will win a match using scikit-learn.
* Measure error and improve our predictions.


File overview:

* `scraping.ipynb` - a Jupyter notebook that scrapes the data.
* `predictions.ipynb` - a Jupyter notebook that makes predictions based on the data.

# Local Setup

## Installation

To follow this project, please install the following locally:

* JupyerLab
* Python 3.8+
* Python packages
    * pandas
    * requests
    * BeautifulSoup
    * scikit-learn
    
## Data

I scraped my data from [FBref](https://fbref.com/en/) to get the first part of this project (`scraping.ipynb`).

If you only want to do the second part of the project (`predictions.ipynb`) you can download `matches.csv`.
