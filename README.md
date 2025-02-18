![225690586-ef6095dc-a2e4-4835-8061-6707adf54c08](https://github.com/code-red-Marshall/Data-Science---BCG-X--Forage/assets/82904501/b9eee2cc-6cca-4b92-8c80-27833f760902)

# Data-Science-and-Analytics-Virtual-Internship-BCG-Forage-

## Business Context
PowerCo is a leading utility company that provides gas and electricity to small and medium-sized enterprises. In the dynamic energy market, customers are presented with a plethora of options, leading to an increasingly competitive environment. PowerCo has been witnessing a surge in customer churn, a term used to describe customers transitioning to other service providers for potentially better offers.

The churn rate has become a pressing issue for PowerCo, prompting them to seek the expertise of BCG to diagnose the underlying reasons for this trend. One hypothesis that emerged from our discussions is the potential impact of “price sensitivity” on customer churn. In essence, we aim to understand the extent to which price influences a customer’s decision to continue or discontinue their association with PowerCo.

## Project Objective
The primary objective of this project is to delve into the churn phenomenon using data science and analytics. We aim to uncover the factors contributing to customer churn and devise strategies to mitigate this issue. The insights derived from this project will be instrumental in shaping PowerCo’s customer retention strategies and ensuring sustainable growth.

## CRISP-ML (Cross-Industry Standard Process for Machine Learning) framework:

- Business Understanding: PowerCo, a major utility company, is experiencing customer churn due to the liberalization of the European energy market. The goal is to predict and manage customer churn in response to price changes to ensure business sustainability.
- Data Understanding: To investigate these hypotheses, we would need the following data from PowerCo:
    - Electricity consumption details, date of joining as a customer, monthly bill, and industry.
    - Churn data that includes details about churned customers.
    - Historical price data of PowerCo.
- Data Preparation: This involves cleaning the data and conducting feature engineering based on the obtained data using techniques like Logistic Regression and Random Forest.
- Modeling: Define a price limit that triggers customer churn and investigate how price changes impact churn. Predictive models could identify customers who are likely to churn based on their current price.
- Evaluation: Evaluate the performance of the predictive models and the impact of the proposed discount strategy on customer churn.
- Deployment: If the evaluation results are satisfactory, deploy the predictive models and the discount strategy. PowerCo is considering a 20% discount to mitigate customer churn.

This plan aligns with the client’s hypothesis that offering a discount might incentivize customers to remain with PowerCo. 

## Task 1 - 
we need to understand PowerCo’s problem that PowerCo is facing at a deeper level and plan how you’ll tackle it. This is called “business understanding & problem framing”.

The AD wants me and Estelle to email him by COB today outlining:

the data that we’ll need from the client, and

the techniques we’ll use to investigate the issue.

## Task 2 - 
The client has sent over 2 data sets (client_data.csv and price_data.csv):

Historical customer data: Customer data such as usage, sign up date, forecasted usage etc
Historical pricing data: variable and fixed pricing data etc
Churn indicator: whether each customer has churned or not

I need to analyze the following using Python:

The data types of each column
Descriptive statistics of the dataset
Distributions of columns

## Analysis :

The visualization provided by Estelle shows how many companies churned vs. how many companies did not churn. We can see from this that the churn rate is approximately 10%. This is actually a very good churn rate, the closer the rate is to 0%, the better.

The next series of visualizations were created in an attempt to try and dive deeper into how churn changes based on other factors (using other columns). This is useful for us to investigate because it may help us to understand factors that drive churn.

In the notebook we visualize churn vs. sales channel, contract type, number of products, number of years and origin/contract offer.

For example:

We see that for sales channel, there are some sales channels that yield customers churning but there are also other sales channels that have no customers churning.
For contract type, we see quite an even split for customers churning. This is interesting because this may suggest that contract type is not a driving factor towards churn rate.

Additionally, for some columns their distributions with churn rate included. This is useful for us to understand because based on the distribution of a column, this could affect our feature engineering later.
We look at the distribution of consumption, subscribed power and forecast in the notebook. 

For example:

We notice that the distribution of consumption is very skewed, this is called a positive skew since it is biased towards lower values on the x axis.
This is interesting because you may decide to treat this column to reduce the skewness later on during feature engineering. But also because we may want to visualize if there are any outliers within this column. 

To investigate outliers, we use a boxplot. From the boxplot we can see that with the column as it is there are definitely some outliers. Once again this is interesting because we may choose to remove some of these outliers later.


## Task 3 -
To create new features for your analysis and upload your completed python file.

## Task 4 - 
- Train a random forest classifier to predict churn
- Evaluate the predictions using evaluation metrics to demonstrate how accurately the model has performed

# Usage:
- Follow the readme.md
- The py notebooks for all the tasks are mentioned. For task 3 and task 4, we have one jupyter file by the name "Feature_engineering_and_modelling_BCG"
- data_with_predictions.csv has the churn prediction column along with the churn prediction percentage column.

# Contributions: 
Feel free to fork this repository, make changes or improvements, and create pull requests. We appreciate your contributions!










