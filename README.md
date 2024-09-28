# Bank Customer Segmentation

This project aims to apply unsupervised machine learning techniques to segment bank customers into distinct groups based on their transactional behavior. The resulting customer segments can be utilized by the bank's marketing department to develop targeted marketing campaigns, optimize resources, and improve customer satisfaction.

## Project Objective

The primary objective of this project is to segment the bank's customers into meaningful clusters to uncover hidden patterns in their spending behavior and financial habits. By doing so, the bank can tailor its services and marketing strategies to the unique needs of each customer segment.

## Approach

1. **Data Preprocessing:** 
   - The dataset contains attributes like `BALANCE`, `PURCHASES`, `CREDIT_LIMIT`, `PAYMENTS`, and more, related to the customers' credit card usage.
   - Features are normalized, and missing values are handled to ensure data quality.

2. **Dimensionality Reduction:**
   - **Principal Component Analysis (PCA)** is applied to reduce the dimensionality of the data and visualize the customer segments in a lower-dimensional space.

3. **Clustering:**
   - The **K-Means** clustering algorithm is employed to segment customers into clusters based on their transactional behavior.
   - The **Elbow Method** is used to determine the optimal number of clusters.

4. **Model Evaluation:**
   - Cluster quality is assessed using metrics like the **Silhouette Score**.
   - Visualizations, including cluster plots and customer profiles, help interpret the segmentation results.

## Data Description

The dataset contains the following attributes:

- **CUSTID:** Identification of the Credit Card holder.
- **BALANCE:** Amount left in the customer's account for purchases.
- **BALANCE_FREQUENCY:** Frequency of balance updates (score between 0 and 1).
- **PURCHASES:** Total amount of purchases made.
- **ONEOFFPURCHASES:** Maximum purchase amount in a single transaction.
- **INSTALLMENTS_PURCHASES:** Total amount of installment purchases.
- **CASH_ADVANCE:** Cash advance amount taken by the customer.
- **PURCHASES_FREQUENCY:** Frequency of purchases (score between 0 and 1).
- **ONEOFF_PURCHASES_FREQUENCY:** Frequency of one-off purchases (score between 0 and 1).
- **PURCHASES_INSTALLMENTS_FREQUENCY:** Frequency of installment purchases (score between 0 and 1).
- **CASH_ADVANCE_FREQUENCY:** Frequency of cash advances (score between 0 and 1).
- **CASH_ADVANCE_TRX:** Number of cash advance transactions.
- **PURCHASES_TRX:** Number of purchase transactions.
- **CREDIT_LIMIT:** Credit limit of the customer.
- **PAYMENTS:** Total amount of payments made by the customer.
- **MINIMUM_PAYMENTS:** Minimum payments made by the customer.
- **PRC_FULL_PAYMENT:** Percentage of full payments made by the customer.
- **TENURE:** Duration of credit card usage.

## Key Steps in the Project

1. **Data Import and Preprocessing:**
   - Import and clean the dataset.
   - Visualize the dataset using Python libraries to understand the distribution and relationships between attributes.

2. **Optimal Number of Clusters:**
   - Use the Elbow Method to find the optimal number of clusters for K-Means clustering.

3. **Customer Segmentation:**
   - Apply K-Means clustering to segment customers into distinct groups based on their credit card usage patterns.

4. **Dimensionality Reduction and Visualization:**
   - Use PCA for dimensionality reduction.
   - Visualize customer segments in 2D space to interpret the results.

5. **Analysis and Insights:**
   - Analyze the characteristics of each customer segment.
   - Provide actionable insights for targeted marketing strategies.

## Libraries and Tools Used

- **Python**
- **Pandas** for data manipulation and analysis.
- **Scikit-Learn** for machine learning algorithms and preprocessing.
- **Matplotlib** and **Seaborn** for data visualization.
- **Streamlit** (optional) for building an interactive web app interface.

## Conclusion

This project demonstrates the application of unsupervised learning techniques like K-Means and PCA for customer segmentation. The segmentation results enable the bank to better understand its customers and tailor its marketing campaigns effectively, ultimately enhancing customer experience and optimizing marketing efforts.


