
## PREDICTION OF SYRIATEL COMPANY CUSTOMER CHURN
### Overview
Due to increased competition there has been concern for determining the churn rate of customers. Since the market is Dynamic customer have options of switching between different telecommunication companies. By utilzing big data in telecom industry it will be possible to predict the churn rate among the customers in this sector and take measures to curb this problem. Predicting customer churn will help telecommunication firms in solving customer needs and increase its retention rates. 

![awesome](E:\phase 3\dsc-phase-3-project-v2-3\images\94357telecom churn.png)
### Business Understanding
#### Business Problem
Since there is high customer churn rate in telecom industry, Seriatel needs to predict the probability of customer churn rate in order to maintain wide customer base. The company needs to retain existing customer since its costly for Seriatel to lose their loyal customers given that acquring new ones is expensive. Customer churn can have significant financial implications for Seriatel, as it can lead to a loss of revenue, market share, and customer loyalty. Customer churn prediction in this case will involve using dataset of Seriatel and machine learning models to identify customers who are at risk of churn, enabling proactive measures to retain them.
#### Objectives 
* Create machine learning models that can predict customer churn by using data to analyze customer features.
* Comparing the build machine learning models and determine the most accurate model in prediction.  
* The analysis aims to identify the specific features that have a significant impact on the customer churn rate in SyriaTel, provide valuable recommendations based on the findings hence help to mitigate churn rates in the company and improve customer retention.
### Data Understanding 
The project utilizes historical customer data, including demographic information and transactional data of Seriatel telecom company. This data is used to build a predictive model that can classify customers as churned or non-churned. The data has 3333 rows and 21 columns and the company is based in California USA. The colunmn tites are as follows:
- state: The state where the customer resides.
- area code: The area code associated with the customer's phone number.
- international plan: A binary variable indicating whether the customer has an international calling plan (1) or not (0).
- voice mail plan: A binary variable indicating whether the customer has a voicemail plan (1) or not (0).
- number vmail messages: The number of voicemail messages the customer has.
- total day minutes: The total number of minutes the customer used during the daytime.
- total day calls: The total number of calls the customer made or received during the daytime.
- total day charge: The total charges incurred by the customer for daytime usage.
- total eve minutes: The total number of minutes the customer used during the evening.
- total eve calls: The total number of calls the customer made or received during the evening.
- total eve charge: The total charges incurred by the customer for evening usage.
- total night minutes: The total number of minutes the customer used during the night.
- total night calls: The total number of calls the customer made or received during the night.
- total night charge: The total charges incurred by the customer for night usage.
- total intl minutes: The total number of minutes the customer used for international calls.
- total intl calls: The total number of international calls the customer made.
- total intl charge: The total charges incurred by the customer for international calls.
- customer service calls: The number of customer service calls made by the customer.
- churn: A binary variable indicating whether the customer has churned (1) or not (0).
- total_calls: The total number of calls made or received by the customer across all periods (day, evening, and night).
- total_charge: The total charges incurred by the customer across all usage periods.
## Data processing 
We checked for missing values, duplicates, categorical and numerical values to ensure that data is clean and in correct formaat for modelling. 
We further removed the class imbalance from the daate and standardize to make date Consistent and uniformity of modelling
Hence this proces This was done to ensured that the data is valid,accurate and complete for modelling
## Data Analysis 
![awesome](dsc-phase-3-project-v2-3/images/intl plan 2.png)

![awesome](dsc-phase-3-project-v2-3/images/intl plan.png)

![awesome](dsc-phase-3-project-v2-3/images/loyal customer.png)

![awesome](dsc-phase-3-project-v2-3/images/output.png)

![awesome](dsc-phase-3-project-v2-3/images/total call.png)

## Summary

This project is an opportunity to expand your data science toolkit by evaluating, choosing, and working with new datasets. Spending time up front making sure you have a good dataset for a solvable problem will help avoid the major problems that can sometimes derail data science projects. You've got this!
