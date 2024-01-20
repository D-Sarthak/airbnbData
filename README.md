# Airbnb Seattle Udacity Project 
Analysis of Airbnb Seattle data for a Udacity Data Scientist project

Motvation: 

This project is a part of Udacity Data Scientist Nanodegree program. 
This project looks at few of the data questions to be answered using the data,
the questions which are being enquired from the data in this project are : 

1. What is the trend for mean price of the listing for each month of the year ?
2. How does the number of lisitings change through the months and is there a trend ?
3. Is there a relation between the trends of listing price and number of lisitngs each month ?
4. What are the top earning neighbourhoods ?
5. What are the top earning Property Types ?
6. What is the average earning of a host & how does all the host perform w.r.t average ?
7. What are some of the attributes which affects the price of a listing & can we predict the price for a listing using these attributes ? 

The CRISP-DM process :

1. We have a look at the data first for the data understanding and asking the right questions
2. After having a look at the data here are few of the observations : 
	1. There are 3 tables in this data set each containing different attributes of airbnb listings :
	2. listing table : This contains details about a listing like gegraphical information, property type,are,region etc.
	3. reviews table : This table contains reviews by customer for each of the listings
	4. calendar table : This contains the information about the availability of listings in a year.
3. Data Prefparation : 
	1. We created 2 funcations to handle the $ in price and columns & another function to handle % in some of the columns
	2. We imputed the missing data for few of the rows
	3. For the data with year 2017 we removed it from the analysis as it was just for the month of January 
	4. Changed datatype for few of the columns such as date,price,available etc
	5. For categorical Variables we used dummy variables in order to be able to analyze them
4. Data Modelling: 
	1. We modelled the data using linear regression in order to predict the prices of a listing 
5. Result Evaluation: 
	1. The results for the modelling are evaluated through the residual vizualization. 
6. Deployment:
	1. This project did not need a deployment