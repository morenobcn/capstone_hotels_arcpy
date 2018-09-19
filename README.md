# Capstone Project:
## Spatial Data Science Applied: ArcPy & Scikit learn for predicting Hotel Room prices.

Repository contains:
1)  Notebook from 1 to 6 with all the analysys and step by step.
2) Toolbox folder that contaisn teh Python toolbox with the ML deployed

Blog Link: https://nycdatascience.com/blog/student-works/spatial-data-science-applied-arcpy-scikit-learn-for-predicting-hotel-room-price

<h2><strong>Objectives and Workflow</strong></h2>
For this capstone project we wanted to be able to estimate the price per night of hotels rooms in London . First we had to gather data regarding the hotels and its prices, and also about features that could help us to explain that price.

In addition to this we also wanted to develop a Machine Learning  algorithm that could be easily distributed and reproducible by non technical colleagues and clients. For this purpose we will be creating a Python Toolbox that uses XGBoost tree algorithm in the background.

As shown in the graphic below we used multiple data sources as well techniques for being able to predict hotel room prices. The main hotels dataset was scraped from Tripadvisor using the Python libraries Scrapy and Selenium. For each hotel we extracted the location, star rating, number and reviews ranking as well as some qualitative information about hotel facilities such as internet, room service, swimming pool and so on.

The main driver of hotel room prices is the location so we also decided to include some of the more relevant characteristics around each hotel that could help us predict its value. Some of this variables are: purchasing power of the population around each hotel, number of housing transactions, distance to tourist points of interest and communication to main airports as well as restaurant data (total number and reviews).

Once all the data was gathered we enriched our hotel dataset with these variables and using scikit learn and XGBoost algorithm we fit a model that was used to predict the hotel room prices. As mentioned before the final ouput is a Python Toolbox (to be used with ArcGIS Pro) that will allow users to run our findings without having a technical background.

&nbsp;

&nbsp;

<a href="http://nycdatascience.com/blog/wp-content/uploads/2018/09/workflow.png"><img class="aligncenter wp-image-37331" src="http://nycdatascience.com/blog/wp-content/uploads/2018/09/workflow.png" alt="" width="1120" height="359" /></a>
