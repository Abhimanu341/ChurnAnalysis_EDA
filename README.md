
# Telecom Churn Data Analysis

This project analyzes a telecom churn dataset to understand customer behavior and identify key factors that contribute to customer churn. The dataset contains various features, including account details, call usage statistics, and customer service interactions. The goal of this analysis is to uncover insights that can help the telecom company reduce churn and improve customer retention.

## Dataset

The dataset used in this analysis is publicly available and contains the following columns:

- **State**: Customer's state (categorical).
- **Account length**: Duration of the customer's account in days (numeric).
- **Area code**: Area code of customer's location (numeric).
- **International plan**: Whether the customer has an international calling plan (Yes/No).
- **Voice mail plan**: Whether the customer has a voicemail plan (Yes/No).
- **Number vmail messages**: Number of voicemail messages (numeric).
- **Total day minutes**: Total minutes of daytime calls (numeric).
- **Total day calls**: Number of daytime calls (numeric).
- **Total day charge**: Total charge for daytime calls (numeric).
- **Total eve minutes**: Total minutes of evening calls (numeric).
- **Total eve calls**: Number of evening calls (numeric).
- **Total eve charge**: Total charge for evening calls (numeric).
- **Total night minutes**: Total minutes of night calls (numeric).
- **Total night calls**: Number of night calls (numeric).
- **Total night charge**: Total charge for night calls (numeric).
- **Total intl minutes**: Total minutes of international calls (numeric).
- **Total intl calls**: Number of international calls (numeric).
- **Total intl charge**: Total charge for international calls (numeric).
- **Customer service calls**: Number of calls to customer service (numeric).
- **Churn**: Whether the customer left the service (True/False).

## Objectives

1. **Data Cleaning**: Verify that the data is free of missing values and outliers.
2. **Exploratory Data Analysis (EDA)**: Perform visual analysis to identify trends and correlations.
3. **Customer Churn Analysis**: Investigate the factors that influence churn using statistical techniques and visualizations.
4. **Insights**: Provide actionable insights that can help improve customer retention.

## Insights

- **Churn Distribution**: The churn rate is visualized using a pie chart and a count plot to compare the number of churned vs non-churned customers.
- **Customer Service Calls**: Churned customers tend to make more customer service calls, which may indicate dissatisfaction.
- **International Plan**: The presence of an international plan impacts churn rates.
- **Area Code**: The analysis shows the churn rates by area code, highlighting whether geographical location has any influence on churn.
- **Total Day Minutes**: Churned customers tend to use fewer total day minutes, indicating potential early signs of disengagement.

## Visualizations

1. **Churn Percentage**: Pie chart showing the proportion of churned and non-churned customers.
2. **Churn vs. Customer Service Calls**: Boxplot comparing the number of customer service calls between churned and non-churned customers.
3. **Day Minutes Distribution**: Histogram comparing total day minutes between churned and non-churned customers.
4. **Churn by Area Code**: Bar chart showing the churn rate by area code.
5. **Churn by Voice Mail Plan**: Count plot showing the churn rate based on the presence of a voicemail plan.

## Installation

To run the project locally, clone this repository and install the necessary dependencies:

```bash
git clone https://github.com/yourusername/telecom-churn-analysis.git
cd telecom-churn-analysis
pip install -r requirements.txt
```

## Requirements

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn

## Usage

Once the dependencies are installed, you can run the Jupyter Notebook or Python script to start the analysis. The notebook contains step-by-step instructions for data cleaning, exploration, and analysis.

