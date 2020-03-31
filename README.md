# PAC-12 Football Statistics Web Scraper

## Introduction
As an avid college football fan, as well as a former Utah Ute, I have always been interested in the statistical nature of college football.  For this project, I built a web scraper that will pull the PAC-12 conference statistics for each time from the [www.cfbstats.com] website.  This can be run weekly to see the overall changes in individual teams. 

## Data Sources Used
This project scrapes data from the [www.cfbstats.com] site.  

## Technologies Used
* Python 3+
* Jupyter Notebook 5.7.8

## Required Packages  
```python
import requests
from bs4 import BeautifulSoup
import lxml.html as lh
import pandas as pd
from IPython.display import Image
```

## Analysis Methods Used  
* Python
* Web Scraping

## Model Deployment
The user should take care when deploying this web scraping utility.  This is based off of the 2019 data structure of the www.cfbstats.com website.  The user may need to make some adjustments for use in future years.   

## Summary of Results
Here is a screenshot of the final Week 12 results from the 2019 football season.  
![week_12.png]
