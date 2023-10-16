# Credit Card Customer Churn Prediction
## Final Project for ADS 505

### Team Members:
Ebad Akhter
Jeremiah Fa'atiliga
Shailja Somani   

****

## Introduction
This repository contains a dataset of credit card customers and their churn status, along with a Python code implementation of a Random Forest model used to predict customer churn. The model aims to identify individual customers who are at risk of churning, which is a crucial task for businesses to retain their customers and ensure their loyalty.

## Dataset
The dataset included in this repository provides information about various attributes of credit card customers, such as their age, gender, education level, usage of credit cards, and more. It also includes the target variable, which indicates whether a customer has churned or not.

## Analysis
In response to a surge in customer credit card cancellations, the bank sought Team 1 to investigate and address dissatisfaction trends. Analyzing a 10,000-customer database, Team 1 has developed innovative models to proactively engage potential churn-risk customers and offer personalized solutions. This strategic initiative aims to mitigate the current 16% churn rate, fostering increased customer satisfaction and retention.

There is information of roughly 10,000 customers in the dataset for discovery of patterns of attrition. We explored the distribution of consumers' credit card cancellations across different education levels, income brackets, gender, and card category. We also investigated the customers age in order to uncover any potential age-related patterns.

## Model
We split that total records of dataset, 10,127, into 70% Training Data and 30% Validation Data for our model. Resulting in 7,088 records for the Train Set, and 3,039 records for Validation Set.

After testing various Machine Learning Models, we compared the Area Under the Curve (AUC), metric that seeks to minimize both false positive & false negative rates, to see which model performed the best. Random Forest Model, that creates many decision trees on various subsets of the data, then combines them all for final predictions, resulted in the highest AUC Metric results and was chosen as the Best Performing Model.

We then remove extraneous features, using recursive feature elimination process and then verify that our top features are correctly identified as well. We also fine-tuned the model to predict customer churn based on the dataset's features.

## Usage
To use this model, follow these steps:

* Clone this repository to your local environment.
* Install the necessary Python packages listed in the requirements file.
* Run the Jupyter Notebook or Python script that contains the Random Forest model implementation.
* The model will predict customer churn based on the provided dataset.

You can also customize and extend the model to suit your specific business needs.

## Contributing
Feel free to contribute to this project by improving the model, adding new features, or suggesting enhancements. Your contributions are highly valued and can benefit the community in better understanding and predicting customer churn in the credit card industry.

Thank you for using this credit card customer churn prediction model!

## References:
Goyal, S. (2020). *Credit Card Customers.* Kaggle. Retrieved Oct 13, 2023, from https://www.kaggle.com/datasets/sakshigoyal7/credit-card-customers/data. \
ChatGPT-3.5 (2021). *OpenAI.* Retrieved Oct 13, 2023, from https://chatgpt.openai.com.
