# Customer Segmentation with RFM K-Means Clustering

This project applies **RFM (Recency, Frequency, Monetary)** analysis to segment customers using the **K-Means clustering** algorithm. The goal is to identify different customer segments based on purchasing behavior to improve marketing strategies and business decisions.

## Project Overview

- **Recency (R)**: How recently a customer made a purchase
- **Frequency (F)**: How often a customer makes a purchase
- **Monetary (M)**: How much money a customer spends

Using these three metrics, K-Means clustering groups customers into segments that share similar behaviors. The project includes an analysis of customer data, segmentation using K-Means, and visualization of the results.

## Dataset

The dataset used in this project is from an online retail store. It is stored in the `OnlineRetail.csv` file and includes the following columns:
- `CustomerID`: Unique identifier for each customer
- `InvoiceDate`: Date of the purchase
- `InvoiceNo`: Unique invoice number
- `TotalAmount`: Total amount spent on the invoice

## Steps

1. **Data Preprocessing**: The dataset is cleaned and prepared by calculating the Recency, Frequency, and Monetary metrics for each customer.
2. **Normalization**: RFM values are normalized using **StandardScaler**.
3. **K-Means Clustering**: The K-Means algorithm is applied to segment customers into different clusters based on their RFM values.
4. **Visualization**: Visualize the clusters and interpret the customer segments.

## Files

- `RFM_KMeans_Clustering.ipynb`: Jupyter notebook with the RFM analysis and K-Means clustering implementation.
- `OnlineRetail.csv`: The dataset used for customer segmentation.

## Requirements

- Python 3.x
- Pandas
- Numpy
- Scikit-learn
- Matplotlib (for visualizations)

You can install the required libraries using pip:

```bash
pip install pandas numpy scikit-learn matplotlib
