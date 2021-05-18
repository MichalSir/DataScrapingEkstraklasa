# DataScrapingEkstraklasa

several program that allows to scrape data about football league Ekstraklasa. Data such as players, teams, matches and stuff like that. Data are scraped from polish website meczyki.pl

## Description Scraping

This is my school project for subject named data analysis and visualization. In the beginning i have collected data from polish website meczyki.pl. Collected data are divided into four files: 
* Stats.csv       Information about statistics like ball possession, goal attempts and so on. 

view from website:

![](imagesRedme/statsWebsite.png)

view of scraped data:

![](imagesRedme/statsScraped.png)

* Summary.csv     Information about all things that occured during match. 

view from website:

![](imagesRedme/summaryWebsite.png)

view of scraped data:

![](imagesRedme/summaryScraped.png)

* Teams.csv       Information lineup with starting lineup and substitutes

view from website:

![](imagesRedme/teamsWebsite.png)

view of scraped data:

![](imagesRedme/teamsScraped.png)

* PlayerList.csv  Information about all players

view from website:

![](imagesRedme/playersWebsite.png)

![](imagesRedme/playerExample.png)

view of scraped data:

![](imagesRedme/playersScraped.png)

## Description Analysis
In this project i am attempting to create several interactive dashboards. 

Already i have created two of them. 

First one is simple histogram representing goals statistics:

![](imagesRedme/DashBoard1.png)

Second one show specific statistics about chosen team:

![](imagesRedme/DashBoard2_1.png)

![](imagesRedme/DashBoard2_2.png)

![](imagesRedme/DashBoard2_3.png)

![](imagesRedme/DashBoard2_4.png)




## Description Summary
There are total of 3 scripts written using Python. Two dedicated for scraping, and third for data analysis. 

## Getting Started

### Dependencies
For scraping I am using Python -> Jupyter Notebook and libraries:

* pandas
* numpy
* requests
* bs4 (BeautifulSoup)
* datetime

For data analysis I am using Python -> JupyterLab and libraries:
* pandas
* dash
* plotly
* dash
* dash_html_components
* dash_core_components
* dash_bootstrap_components
* jupyter_dash

## Authors
Michał Sir
