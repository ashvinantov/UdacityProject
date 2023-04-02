# UdacityProject
Data Science Project



The business use case which i was trying to understand is

1. find which are the most correlated features for defining price
2. Create a regression model to define price of a property
3. Visualize trend of Price across States to understand which area is the most contributing

I have tried to follow CRISP-DM Process

Steps Involved
1. Analyse the given dataset - Listings.csv
2. Cleaning the data- Clean the data which have null values by using the techniues mentioned in the course
3. Create a correlation plot to analyze which are the most relevant features which answers my question1
4. Create a linear regression model and try to predict the prices
5. Analyze the rsquare value and confirm if this model can be taken forward

Link to Medium BLog post is shared hereby

* Business Understanding
* Data Understanding
* Prepare Data
* Data Modeling(Optional)
* Evaluate the Results



* Business Understanding
    - Brief description - This project is worked upon AirBnB Data which has three different datasets
        1. Listings.csv, which gives you details related to listings of hotels
        2. reviews - All related to reviews of each site
        3. calendar - listing of each propery along calendar days
    - Question 1 - find which are the most correlated features for defining price
    - Question 2 - Create a regression model to define price of a property
    - Question 3 - Visualize trend of Price across States to understand which area is the most contributing
* Data Understanding
    - Access and Explore - The data was explored and couple of relevant columns were observed. I was able to understand which among them were relevant for my usecase and which were not
* Prepare Data
    - Wrangle and Clean - The data was cleaned by understanding the missing values, and either filling null entries with nan or 0
* Modeling(optional)
    - Fit model - A linear regresssion model was created using the features which were extracted by analysing the correlation of price with relevant features
    - Validate the model - Using r squar value, the values were decided if it is a good candidate or not
* Question 1
    - Analyse/Visualize - Correlation matrix based on relevant columns was created and stored it into an excel which is shared and the output was then analyzed. Based on that the columns mentioned in yellow were considered to be potential independent features to the model.
* Question 2
    - Analysis - Regression Model was created on top of the correlated relevant features and a model with rsqare value of 0.212 was obtained. Anything greater than 0.2 looks good an hence moving forward
* Question 3
    - Analyse - the property_type across and the prices
    - Explain the visualisation - Guest houses and boats as obvious have the highest average pricing.
                                   Villas and apartments are also showing a decent pricing  
* Evaluation
    - Findings
