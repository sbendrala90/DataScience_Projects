﻿# CapStone 1 Project Proposal

## 1. Walmart Sales Prediction
----
see [Kaggle](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting)

### Problem 
historical sales data for 45 Walmart stores located in different regions. Each store contains many departments, and we need to project the sales for each department in each store. To add to the challenge, selected holiday markdown events are included in the dataset. These markdowns are known to affect sales, but it is challenging to predict which departments are affected and the extent of the impact.


### Who might care? 
Travel planner and booking companies such as booking.com, expedia.com, kayak.com, priceline.com, etc. can use such a model to predict the likelihood of the cancellation of a flight. They can then inform their customers well in advance, even before the airlines' management informs the passengers, about the probability of the cancellation of their upcoming flight. From the traveler's point of view, it would be very convenient for them. On the other hand, such a predictive model would enhance the product base of travel planner companies. Moreover, there is a possibility of developing an app which travelers can use to know about their flight cancellation likelihood in advance.

### Data
The flight data will be acquired from the Bureau of Transportation Statistics. This data contains information about each flight and their on-time performance, including date of flight, carrier type, origin and destination airports, flight distance, delay, cancellation, diversion etc. In this project, we will mainly focus on the data collected during 2015-2016, and on some selected airports only. Often the flight cancellations are caused due to bad weather conditions. Therefore, it is also important to have the hourly weather data which will be accessed through wunderground.com API, for example. We will acquire the weather data for those selected airport locations and only for years 2015 and 2016.

### Modeling approach
 Since we want to predict the likelihood of a flight getting canceled, a supervised classification algorithm is a perfect choice to build the predictive model. The classification algorithm not only classifies classes (in our case, two classes: “canceled” and “not canceled”) but also predict the probability of each class. This data set contains imbalanced classes (only about 1-2% of the data will have "canceled" flag in them), which makes the project challenging. We plan to use different approaches to tackle the imbalanced class issue and choose the best one. Also, we will try various classification algorithms and pick the one which performs best.

### Possible limitations: 
The prediction of the model will depend on how good the prediction of the weather is, say after 3 days. In other words. if we want to predict the likelihood of the flight cancellation for a flight which is scheduled after 3 days, we would need to know the weather after 3 days (which we do not know "accurately" today). This means that the model will predict better if the weather prediction is better or if we are trying to predict the flights not far ago than the scheduled departure.


----

### Deliverables:

1. **Codes (notebooks) for**:

    a. data acquisition

    b. data cleaning

    c. data exploration analysis

    d. machine learning model development

2. **Report on the capstone project**:
3. **Presentation on the capstone project**:


## 2. Credit Fraud Transactions

see [Kaggle](https://www.kaggle.com/samkirkiles/credit-card-fraud/data)