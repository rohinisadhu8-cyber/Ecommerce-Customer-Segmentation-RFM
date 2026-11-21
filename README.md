# E-Commerce Customer Segmentation using RFM Analysis

## Project Overview
This project focuses on E-Commerce Customer Segmentation using RFM (Recency, Frequency, Monetary) Analysis. It analyzes customer purchasing behaviour and divides customers into different groups based on their transaction history.

The main objective is to identify valuable customers, loyal customers, at-risk customers and lost customers to help businesses improve customer retention and marketing strategies.

## Objectives
- Analyze customer purchasing behaviour.
- Perform data cleaning and preprocessing.
- Calculate Recency, Frequency and Monetary values.
- Assign RFM scores to customers.
- Identify different customer segments.
- Apply K-Means clustering.
- Visualize customer segments using charts.
- Generate business recommendations.

## Dataset
**Dataset Name:** Online Retail Dataset

**Source:** UCI Machine Learning Repository

Dataset Link: https://archive.ics.uci.edu/dataset/352/online+retail

The dataset contains online retail transaction details, including:
- Invoice Number
- Stock Code
- Product Description
- Quantity
- Invoice Date
- Unit Price
- Customer ID
- Country

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Excel
- Power BI

## Project Methodology

### 1. Data Collection
Collected the Online Retail dataset from the UCI Machine Learning Repository.

### 2. Data Cleaning
- Removed missing Customer IDs.
- Removed cancelled invoices.
- Removed invalid quantities and prices.
- Converted invoice dates into datetime format.

### 3. RFM Analysis
Calculated three important customer metrics:

- **Recency:** How recently a customer purchased.
- **Frequency:** How frequently a customer purchased.
- **Monetary:** How much money a customer spent.

### 4. RFM Scoring
Assigned scores from 1 to 5 based on customer purchasing behaviour.

### 5. Customer Segmentation
Classified customers into:
- Champions
- Loyal Customers
- Potential Loyalists
- At-Risk Customers
- Lost Customers
- Need Attention

### 6. K-Means Clustering
Applied the K-Means machine learning algorithm to group customers into four clusters.

### 7. Data Visualization
Created charts to understand customer behaviour, spending patterns and customer clusters.

## Project Structure

```text
Ecommerce-Customer-Segmentation-RFM/
│
├── Ecommerce_Customer_Segmentation_RFM.ipynb
├── RFM_Customer_Analysis.xlsx
├── Customer_Segmentation_Dashboard.pbix
├── Business_Recommendation.docx
├── Visualizations/
│
└── README.md
```

## Expected Outcomes
- Identification of valuable customers.
- Understanding customer purchasing patterns.
- Identification of customers at risk of leaving.
- Improved customer retention strategies.
- Data-driven marketing recommendations.

## Business Recommendations
- Provide exclusive rewards to Champions.
- Offer loyalty benefits to regular customers.
- Send personalized offers to At-Risk Customers.
- Use reactivation campaigns for Lost Customers.
- Provide targeted promotions to customers who need attention.

## Conclusion
This project demonstrates how RFM Analysis and K-Means Clustering can be used to understand customer behaviour and perform effective customer segmentation. The analysis helps businesses make better marketing decisions, improve customer relationships and increase customer retention.

## Author
**Name:** Rohini Sadhu

**Internship Organization:** Veda Technology

**Project:** E-Commerce Customer Segmentation using RFM Analysis

**Domain:** Data Analytics / Data Science

## Acknowledgement
I would like to thank Veda Technology for providing the opportunity to work on this project and improve my practical knowledge of Python, data analytics and machine learning.
