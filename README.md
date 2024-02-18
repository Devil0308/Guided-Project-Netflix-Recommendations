## Problem Statement

- Customer Behaviour and it's prediction lies at the core of every Business Model. From Stock Exchange, e-Commerce and Automobile to even Presidential Elections, predictions serve a great purpose. Most of these predictions are based on the data available about a person's activity either online or in-person.
- Recommendation Engines are the much needed manifestations of the desired predictability of user activity. Recommendation Engines move one step further and not only give information but put forth strategies to further increase users' interaction with the platform.
- In today's world OTT platform and Streaming Services have taken up a big chunk in the Retail and Entertainment industry. Organizations like Netflix, Amazon etc. analyse User Activity Pattern's and suggest products that better suit the user needs and choices.

---
## Project Objective 

The purpose of this Project Project we will be
creating one such Recommendation Engine
from the ground-up, where every single user,
based on there area of interest and ratings,
would be recommended a list of movies that
are best suited for them.

---

## Data Description:

- The dataset is taken from kaggle known as netflix prize dataset and is in specific format.
- So we have to use pandas slicing to get the data from the dataset in a required format.
- Provided format is of rows 24058263 and columns 2 having headers 0 and 1.
- Where 0th columns contains both customer Id and movie Id for the individual customer and 1st column contains movie ratings.
- After the manipulation of provided dataset we get 24058262 rows and 3 columns
    - *Customers Id*:- Columns contains customer Ids
    - *Movies Id*:- Have Ids of the corresponding movies.
    - *Ratings*:- Contains ratings of movies given by particular individuals.
 
--- 

## Data Preprocessing

The pre-processing of the data included the following steps:
1. Step 1: Load Data
2. Step 2: Perform ***Exploratory Data Analysis***
    - Confirm number of records in the data and how they are distributed
    - Check data types
    - Check for missing data, invalid entries, duplicates
    - Check for data arrangement and how they are present as all necessary columns are provided.
    - In this case as given below:-
        - Provided Dataset:- 
3. Step 3: See relations between independent and dependent variables and make inferences.
4. Step 4: Model Predictions, two approaches:
    - Linear Regression Models.
    - Time Series Model (ARIMA, SARIMAX).
5. Step 5: Forecast
6. Step 6: Compare result from different models
