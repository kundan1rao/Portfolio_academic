---
author: Kundan K. Rao
categories:
- Data_visulization
- R
date: "2021-11-22"
draft: false
excerpt: In this project i have made a data visulization map of India of Covid-19 cases in as of 1st October 2021.
featured: true
layout: single-sidebar
links:
- icon: r-project
  icon_pack: fab
  name: Rpubs (live project link)
  url: https://rpubs.com/kundan1rao/covid-19-india-map
- icon: github
  icon_pack: fab
  name: Github code Repository
  url: https://github.com/kundan1rao/Covid19-map
- icon: registered
  icon_pack: fas
  name: Run On Rstudio cloud
  url: https://rstudio.cloud/project/3267423
subtitle: "Data visulization (map) of confirmed cases of Covid-19 as of 1st october 2021 "
tags:
- map
title: Covid-19 India map
---


#### When you visit the live project link, you will see the following maps:-

![App Screenshot](Images/Rplot0111.png)

![App Screenshot](Images/Rplot1111.png)


I have made a statc and a interective map of India to visualize COVID-19 confirmed cases in India state wise as of 1st october 2021.


#### R programming packages used for making map:-
- Map made with package `tmap`
- `tmap` is very handy for making thematic maps in `r`


#### When you open the github repository link or the Rstudio cloud link, you will see the following files:-
* **India_State_Shapefile** :- Contains the shape file of India.
* **Code rmarkdown** :- Contains the Rmd file of R Code
* **Code-rmarkdown** :- Contains the HTML file of Maps
* **states** :- Contains the COVID-19 India data
* **Images** :- Contains screenshot of maps


#### Data was obtained from the following websites:-
##### Website
[https://www.covid19india.org/](https://www.covid19india.org/)

##### Data Download Link
[https://data.covid19india.org/csv/latest/states.csv](https://data.covid19india.org/csv/latest/states.csv)


#### Environment
I have made this project with following environment:-

**`RStudio Version 1.4.1717`**

**`R 4.1.1`**

