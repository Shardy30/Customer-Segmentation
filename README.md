# Customer Segmentation Project

## Project Overview
This project uses a dataset of E-commerce user purchases to develop a model capable of classifying customers into segments and predicting the future purchases of new customers over the next year based on their first purchase.

## Goals
1. *Customer Segmentation*: Classify customers into distinct groups based on purchasing behavior.
2. *Purchase Prediction*: Predict the purchases a new customer will make in the subsequent year from their first purchase.

## Dataset
The project utilizes an E-commerce dataset that contains details of user purchases. The dataset includes the following attributes:
- Customer ID
- Invoice ID
- StockCode
- Description
- Quantity
- Invoice Date
- Unit Price
- Country

## Methodology
The project involves several key steps:
1. *Data Preparation*: Clean and preprocess the dataset to handle missing values and outliers.
2. *Exploratory Data Analysis (EDA)*: Analyze the dataset to understand the distribution and relationship of the variables.
3. *Feature Engineering*: Extract and select features relevant to the customer segmentation and purchase prediction.
4. *Model Development*:
   - The segmentation will be performed using clustering algorithms, such as SVC, logistic Regression, K-Nearesr Neighbours, Decision Trees, Random Forest. The optimal number of clusters will be determined using techniques such as elbow method or silhouette analysis.
   - Build predictive models to forecast future purchases based on the initial purchase data.
5. *Model Evaluation*: Assess the performance of the models using metrics such as silhouette score and accuracy.

## Technologies Used
- Python: Primary programming language.
- Pandas, NumPy: Data manipulation and numerical computing.
- Matplotlib, Seaborn: Data visualization.
- Scikit-learn: Machine learning and data preprocessing.

## Installation and Setup
1. Clone the repository:
   bash
   git clone [repository-url]
   
2. Install required Python packages:
   bash
   pip install -r requirements.txt
   
3. Run the Jupyter Notebook:
   bash
   jupyter notebook Cust_segmentation_online_retail.ipynb
   

## Conclusion
This project demonstrates the application of machine learning techniques in understanding customer behavior and aiding in decision-making for marketing strategies.
