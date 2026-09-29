# IT Service Customer Purchase Prediction & Recommendation

An end-to-end Machine Learning and Power BI project for an IT services company to predict customer purchase behavior and recommend relevant IT services.

## Project Overview

The objective of this project is to:

- Predict whether a customer is likely to purchase an IT service.
- Identify suitable IT services based on customer technology usage.
- Present business insights through an interactive Power BI dashboard.

## Tech Stack

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Power BI

## Machine Learning

Three classification models were developed and evaluated:

- Logistic Regression
- Decision Tree
- Random Forest

### Model Results

| Model | Accuracy | Precision | Recall | F1 Score |
|---|---:|---:|---:|---:|
| Logistic Regression | 67.9% | 70.8% | 78.3% | 74.3% |
| Decision Tree | 57.2% | 64.6% | 62.0% | 63.2% |
| Random Forest | 67.6% | 69.6% | 80.8% | 74.8% |

## Service Recommendation

A rule-based recommendation system was developed using customer technology usage to recommend:

- Cybersecurity
- Cloud Services
- Data Analytics
- AI Solutions
- Advanced IT Solutions

Customers predicted not to purchase are assigned **No Offer**.

## Power BI Dashboard

The interactive dashboard includes:

- Total Customers
- Total Purchases
- Purchase Rate
- Predicted Buyers
- Customer analysis by Industry and Company Size
- Purchase analysis by Lead Source
- Recommended Services
- Customer Segments
- Interactive slicers
- Customer-level recommendations

## Dataset

The dataset contains **5,000 customer records** with information about:

- Customer demographics
- Company information
- IT budget and revenue
- Customer engagement
- Technology usage
- Previous purchases
- Lead source
- Purchase outcome

## Key Results

- 5,000 customers analyzed
- 2,958 recorded purchases
- 59.16% purchase rate
- 3,054 predicted buyers
- Random Forest achieved the highest F1 score of 74.8%

## Project Structure

```text
IT-Service-Customer-Purchase-Prediction/
│
├── data/
│   └── IT_Service_Customer_Data.csv
│
├── notebook/
│   └── IT_Service_Customer_Purchase_Prediction.ipynb
│
├── powerbi/
│   └── Technova_Dashboard.pdf
│
├── images/
│   └── dashboard.png
│
└── README.md
