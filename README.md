# Insurance Data Analysis 

## Project Overview

This project performs Exploratory Data Analysis (EDA) on an insurance dataset to understand customer demographics, policy preferences, and premium behavior. The analysis focuses on discovering patterns and insights using data visualization and statistical techniques, without applying machine learning models.

## Objectives

- Analyze customer distribution across city and region codes
- Identify the most common insurance and policy types
- Study the relationship between age range, policy duration, and premium amount
- Understand how accommodation type affects spouse and policy holding behavior
- Generate meaningful business insights using visualizations

## Tools and Technologies

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- kaggle

## Dataset Description

The dataset contains customer-level insurance information used to analyze demographic patterns, policy preferences, and premium behavior. Each row represents an individual customer record with the following features:

- ID: Unique identifier for each customer
- City_Code: Encoded city identifier where the customer resides
- Region_Code: Encoded regional identifier
- Accomodation_Type: Indicates whether the customer lives in an owned or rented accommodation
- Reco_Insurance_Type: Recommended insurance type (Individual or Joint)
- Upper_Age: Upper age limit of the insured individual(s)
- Lower_Age: Lower age limit of the insured individual(s)
- Is_Spouse: Indicates whether the policy includes a spouse
- Health Indicator: Categorical indicator representing the customer’s health condition
- Holding_Policy_Duration: Duration (in years) for which the policy has been held
- Holding_Policy_Type: Type/category of the policy held
- Reco_Policy_Cat: Recommended policy category
- Reco_Policy_Premium: Recommended insurance premium amount
- Response: Target variable indicating whether the customer accepted the recommended policy

## Analysis Performed

- Data cleaning and preprocessing
- GroupBy analysis to calculate average premiums
- Univariate and bivariate analysis
- Count plots for categorical variables
- Line plots for policy duration vs premium
- Density plots and distribution analysis

## Key Insights

- A small number of city codes account for the majority of customers
- Individual insurance policies are significantly more common than joint policies
- Average policy premiums vary by region and policy duration
- Renters slightly outnumber homeowners, but homeowners are more likely to have spouses
- Customer activity shows a long-tail distribution across cities

## Conclusion

This project demonstrates how Exploratory Data Analysis can be used to extract actionable insights from insurance data. The visualizations and statistical summaries provide a clear understanding of customer demographics, policy trends, and premium behavior, making the analysis valuable for business and decision-making purposes.

## Author

Akisha Bhujel
Github - https://github.com/akisavujel
kaggle - https://www.kaggle.com/akisavujel

## Tags

#DataAnalysis
#ExploratoryDataAnalysis
#Python
#Pandas
#Matplotlib
#Seaborn
#InsuranceAnalytics
#DataVisualization
