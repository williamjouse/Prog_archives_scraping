# Prog Archives web scraping and exploratory data analysis

In this project, we perform web scraping of a website. Web scraping is extracting information from one or more websites in an automated way. 
We usually do this when we want data that is not available through APIs.

The target site is [Prog Archives](http://www.progarchives.com/). It is a progressive rock website with an active community that 
indexes various genres, bands, and albums, with ratings and comments. This website is the most complete and progressive rock resource. 
Prog Archives has a robust search engine that allows us to search the albums of each year, by genre and country.

In the [progarchives_scraping.ipynb](https://github.com/williamjouse/Prog_archives_scraping/blob/main/progarchives_scraping.ipynb) 
we implement the web scraping and save the raw data into data/raw folder. In the following, we execute the exploration data analysis 
[progarchives_analysis.ipynb](https://github.com/williamjouse/Prog_archives_scraping/blob/main/progarchives_analysis.ipynb)
using the data from web scraping. We save the figures generated in the analysis into the figures directory. 