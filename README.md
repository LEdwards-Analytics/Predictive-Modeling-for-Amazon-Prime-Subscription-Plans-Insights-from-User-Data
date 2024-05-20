# Amazon Prime Subscriber

Amazon Prime subscriber EDA and ML Model to determine subscription plan (Annual vs Monthly)

## Description

The main purpose of analyzing Amazon Prime Subscriber data is to:
1. Understand the demographic and behavioral patterns of Amazon Prime subscribers.
2. Explore the data to determine what features to use in the model.
3. Create a model to provide valuable insights into user behavior and preferences, enabling data-driven decision-making for subscription-based businesses.

## Data Source 📊

The data is from: 
https://www.kaggle.com/datasets/arnavsmayan/amazon-prime-userbase-dataset 

It includes the following columns:

**User ID:** Numeric ID for the user

**Name:** User's name

**Email Address:** User's email address

**Username:** Username

**Date of Birth:** Date of Birth of the user

**Gender:** User's gender

**Location:** User's Country

**Membership Start Date:** Start date of the Amazon Prime membership

**Membership End Date:** End date of the membership

**Payment Information:** Payment method used (Visa, Mastercard, Amex)

**Renewal Status:** Setting of renewal on subscription (Manual vs Automatic)

**Usage Frequency:** Frequency of platform usage (Occasional, Regular, Frequent)

**Purchase History:** Most frequently purchased items

**Favorite Genres:** Favorite genre of content

**Devices Used:** Device used to access the platform

**Engagement Metrics:** Engagement level (Low, Medium, High)

**Feedback/Ratings:** Average feedback/ratings given by the user

**Customer Support Interactions:** Number of interactions with customer support

**Subscription Plan:** Type of subscription plan (Annual vs Monthly).

## Getting Started

### Built with 🛠️

* pandas
* numpy
* matplotlib.pyplot
* seaborn
* datetime
* sklearn

## Exploratory Data Analysis (EDA)
Conducted exploratory data analysis to gain insights into the dataset.
Explored the distributions of key variables and identified potential patterns or trends. (Gender, Genres, Feedback/Rating)

## Model Building
* Utilized various machine learning algorithms, including Logistic Regression, Decision Tree, and Random Forest to predict the target variable.
* Evaluated the performance of each model using accuracy, precision, and recall metrics.
  

## Results
The Decision Tree model achieved an accuracy of 54.667% on the test dataset.
Precision and recall for the Decision Tree model were 56.265% and 60.560%, respectively.

## Conclusion
The Decision Tree model outperformed other models in terms of accuracy, precision, and recall and was selected as the final model.
The model had low numbers, but 54.667% was the highest I could manage to get the model accuracy, changing test/train splits, changing the selected features, and testing different models.

This model could greatly benefit from more useful customer data. The dates related to customers were all 1 year in length, as this isn't realistic or predictive towards their subscriptions, it also doesn't add to
the performance of the model.


### Authors

Luke Edwards (me)

https://github.com/Dream3223

### License

This project is licensed under the MIT License - see the LICENSE.md file for details
