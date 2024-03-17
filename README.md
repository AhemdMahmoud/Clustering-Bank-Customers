# Clustering-Bank-Customers🎉

# Project Objective:🐱‍🏍

### This project aims to categorize customers of bank accounts using advanced unsupervised learning techniques. By leveraging various methodologies and tools, we aim to uncover meaningful patterns within the data and effectively segment customers into distinct categories.
![Image Description](https://github.com/AhemdMahmoud/Clustering-Bank-Customers/raw/main/TSNE.png)
 ## 🤳 The primary objective of this project is to:
 ## 1: `Employ` advanced unsupervised learning techniques to categorize customers based on their banking behavior.
 ##2: `Determine` the optimal number of clusters using methods such as the Elbow method, Silhouette score, statistical gap analysis, and hierarchical clustering, and some other techniques.
## 3: `Validate` clustering results and explore dependencies among clusters using ANOVA tests.
## 4: `Visualize` each step of the process using t-SNE (t-distributed Stochastic Neighbor Embedding) for enhanced understanding and interpretation.

# 🌟 Business Understanding:
### This case requires to develop a customer segmentation to define marketing strategy. The sample Dataset summarizes the usage behavior of about 9000 active credit card holders during the last 6 months. The file is at a customer level with 18 behavioral variables

# Data Dictionary for Credit Card dataset✌ :-


| Column Name                     | Description                                                                                                               |
|---------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| CUSTID                          | Customer ID (Categorical)                                                                                                |
| BALANCE                         | Remaining balance amount in their account for purchases                                                                   |
| BALANCEFREQUENCY               | How frequently the balance is updated, scored between 0 and 1 (1 = frequently updated, 0 = not frequently updated)      |
| PURCHASES                       | Amount of purchases made from the account                                                                                 |
| ONEOFFPURCHASES                 | Maximum purchase amount done in one-go                                                                                    |
| INSTALLMENTSPURCHASES           | Amount of purchases done in installment                                                                                   |
| CASHADVANCE                     | Cash in advance given by the user                                                                                         |
| PURCHASESFREQUENCY              | How frequently purchases are being made, scored between 0 and 1 (1 = frequently purchased, 0 = not frequently purchased)|
| ONEOFFPURCHASESFREQUENCY        | How frequently one-off purchases are being made, scored between 0 and 1 (1 = frequently made, 0 = not frequently made)   |
| PURCHASESINSTALLMENTSFREQUENCY  | How frequently installment purchases are being made, scored between 0 and 1 (1 = frequently done, 0 = not frequently done)|
| CASHADVANCEFREQUENCY            | How frequently cash in advance is being taken                                                                             |
| CASHADVANCETRX                  | Number of transactions made with "Cash Advance"                                                                           |
| PURCHASESTRX                    | Number of purchase transactions                                                                                           |
| CREDITLIMIT                     | Credit limit for the user                                                                                                 |
| PAYMENTS                        | Amount of payments done by the user                                                                                       |
| MINIMUM_PAYMENTS                | Minimum amount of payments done by the user                                                                               |
| PRCFULLPAYMENT                  | Percentage of full payment paid by the user                                                                               |
| TENURE                          | Duration of credit card service for the user                                                                              |
