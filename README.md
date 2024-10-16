# Flight-Price-Prediction

Check out the consolidated Project Overview on Notion : https://windy-geese-6b2.notion.site/FLIGHT-PRICE-PREDICTION-USING-LINEAR-REGRESSION-bbbded6fbe5e4fd8a80cd0fc735a4339?pvs=4

## OBJECTIVE

The objective of the study is to **analyse the flight booking dataset** obtained from “Ease My Trip” website and to conduct various statistical hypothesis tests in order to get meaningful information from it. The **'Linear Regression' statistical algorithm would be used to train the dataset and predict a continuous target variable.**

'EaseMyTrip' is an internet platform for booking flight tickets, and hence a platform that potential passengers use to buy tickets. A thorough study of the data will aid in the discovery of valuable insights that will be of enormous value to passengers.

The aim of our study is to answer the below research questions:

*Assume that all the assumptions are satisfied*

- **Does airline price depend upon the airline brand**
- **Develop a regression model for predicting flight prices and demonstrate its predictive capabilities by inputting a random sample for price prediction**

## DATA

Source: https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction?datasetId=1957837&language=Python

**Octoparse** scraping tool was used to **extract data** from the website. Data was collected in two parts: **one for economy class tickets and another for business class tickets.** A total of 3**00261 distinct flight booking** options were extracted from the site. Data was collected for 50 days, from **February 11th to March 31st, 2022**. The data source was secondary data and was collected from the “Ease My Trip” website.

## DATASET

The dataset contains information about flight booking options from the website “EaseMyTrip” for flight travel between India's top 6 metro cities. There are 300261 data points and 11 features in the cleaned dataset.

The various features of the cleaned dataset are explained below:

✈️**Airline:** The name of the airline company is stored in the airline column. It is a categorical feature having 6 different airlines.

✈️ **Flight:** Flight stores information regarding the plane's flight code. It is a categorical feature.

✈️ **Source City:** The city from which the flight takes off. It is a categorical feature having 6 unique cities.

✈️ **Departure Time:** This is a derived categorical feature obtained created by grouping time periods into bins. It stores information about the departure time and has 6 unique time labels.

✈️ **Days Left:** This is a derived characteristic that is calculated by subtracting the trip date from the booking date. (10th February 2022)

✈️ **Price:** The target variable stores information on the ticket price.

✈️ **Stops:** A categorical feature with 3 distinct values that stores the number of stops between the source and destination cities.

✈️ **Arrival Time:** This is a derived categorical feature created by grouping time intervals into bins. It has six distinct time labels and keeps information about the arrival time.

✈️ **Destination City:** The city where the flight will land. It is a categorical feature having 6 unique cities.

✈️ **Class:** A categorical feature that contains information on seat class; it has two distinct values: Business and Economy.

✈️ **Duration:** A continuous feature that displays the overall amount of time it takes to travel between cities in hours.

## KEY LEARNINGS 🛩️ :

⏬ **ANOVA (Analysis of Variance)** 

**ANOVA (Analysis of Variance)** is a statistical technique used to analyze the **differences among group means in a sample.** It assesses whether the **means of two or more groups are statistically significantly different from each other.**

⏬ **LINEAR REGRESSION**

Linear regression is **a statistical method that predicts the relationship between two variables**.

⏬ **ONE-HOT ENCODING**

**One-hot encoding** is a technique used in machine learning and data preprocessing to **convert categorical data into a binary (0 or 1) format.** It's commonly used when you have **categorical variables that are not ordinal** in nature. 

Each category is represented by a binary column, and only one of these columns is "hot" (set to 1) at a time, indicating the category for that particular data point.

## ****CONCLUSION****

### **HYPOTHESIS TESTING I (PRICE VARIATION WRT AIRLINES) :**

**RESULT :**

The **p-value, which is lower than the chosen alpha level,** leads us to **reject the null hypothesis with 95% confidence.**

There is **statistically significant difference in the price with respect to the airlines,** as per the ANOVA TEST.

### **LINEAR REGRESSION :**

**RESULT :**

We successfully developed a **linear regression model for predicting flight prices** and demonstrate its predictive capabilities by **inputting a random sample for price prediction.**

## **THANK YOU!**
