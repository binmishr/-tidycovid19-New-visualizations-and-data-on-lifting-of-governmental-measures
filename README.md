# -tidycovid19-New-visualizations-and-data-on-lifting-of-governmental-measures

The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

A Brief Introduction
======================

As the Covid-19 pandemic is affecting more and more countries around the globe, I included additional visualizations options into the {tidycovid19} package so that it becomes easier to compare the spread of the virus across countries. Also, I use this post to take a quick look on some countries that start lifting their governmental measures. See for yourself:

As we all know, the Covid-19 pandemic spreads around the globe. While traditional time-series based displays (like the ones provided by plot_spread_covid19() and show-cased in this blog post and this shiny app are very helpful to study the spread of the virus over a limited set of countries, the graphs quickly become overwhelming when you want to compare multiple countries.

This is why I decided to include two additional visualization approaches into the {tidycovid19} package: Maps and Covid-19 Stripes. Let me start with the latter.

Stripe displays (is there a more official name? I borrowed this term from the well-known Warming Stripes display) are an excellent tool to quickly identify patterns in time-series data. Also, I find them visually appealing. So, meet the “Covid-19 Stripes”. Below, you see the smoothed daily number of deaths for countries that have more than 10,000 confirmed cases in total.

# library("tidycovid19")

library(tidyverse)
library(tidycovid19)

Stripes Display : https://en.wikipedia.org/wiki/Warming_stripes
