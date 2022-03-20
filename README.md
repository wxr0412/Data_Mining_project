# Data_Mining_project
Price Analysis of Amsterdam Airbnb
The data set we use for this project is downloaded from Kaggle with 6 csv files： ( https://www.kaggle.com/erikbruin/airbnb-amsterdam ). 
The 'listings' file contains all the advertisements in Amsterdam on December 6th, 2018. Based on this dataset, our group want to estimate 
the price and sales of the apartment listed on Airbnb Platform. Firstly, we need to do some data wrangling work before analysis.

In this project, we analyzed the Airbnb houses in Amsterdam using the Airbnb data and the information of neighborhoods provided by Foursquare API. 
In the stage of data preprocessing, we use the "3-sigma rule" to remove some housing information with abnormal prices at first. 
Next, in order to process the latitude and longitude information, we use the k-means algorithm to block regions with similar prices 
to generate regions close to various locations. Finally, we use natural language processing technology to analyze the house naming, 
and get the first few words with the most occurrences, so as to study the relationship between naming and price. After the initial 
processing of the features, we also conduct a causal analysis of these features and rental prices, looking for the features that really
act as causes that affect the rental price.

In the modeling process, we used eight classic regression models (4 linear models and 4 non-linear models) to predict the price of the 
properties and analyzed the most influencing factors to the price of a property and compare the performance of different models. 
Based on the above analysis, several recommendations were proposed to people who want to rent their house on Airbnb and 
people who plan to live in a local place in Amsterdam. However, this analysis may not adapt to other city's Airbnb house price 
since different cities have their own characteristics, and thus, a different composition of price influencing factors.
