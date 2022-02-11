# [Customer Clustering using Machine Learning]

**Zijing XUE**

**DAFT NOV 2021**

## Overview

Include the following points in your overview:

* Help the company to better understand their customers by separating customers into groups that reflect similarities among them.
	* ROI: modify products based on target customers needs.
	* Customer satisfaction: serve customers with different shopping behaviors by attractive campaigns and customer service.

## Data Preparation

### Overview:

* My data set is about customers of a retail company
* I found my dataset on Kaggle: \
 https://www.kaggle.com/imakash3011/customer-personality-analysis
* size: 2240 rows x 29 
* column description:

#### People

* ID: Customer's unique identifier
* Year_Birth: Customer's birth year
* Education: Customer's education level
* Marital_Status: Customer's marital status
* Income: Customer's yearly household income
* Kidhome: Number of children in customer's household
* Teenhome: Number of teenagers in customer's household
* Dt_Customer: Date of customer's enrollment with the company
* Recency: Number of days since customer's last purchase
* Complain: 1 if the customer complained in the last 2 years, 0 otherwise

#### Products

* MntWines: Amount spent on wine in last 2 years
* MntFruits: Amount spent on fruits in last 2 years
* MntMeatProducts: Amount spent on meat in last 2 years
* MntFishProducts: Amount spent on fish in last 2 years
* MntSweetProducts: Amount spent on sweets in last 2 years
* MntGoldProds: Amount spent on gold in last 2 years
 
#### Promotion

* NumDealsPurchases: Number of purchases made with a discount
* AcceptedCmp1: 1 if customer accepted the offer in the 1st campaign, 0 otherwise
* AcceptedCmp2: 1 if customer accepted the offer in the 2nd campaign, 0 otherwise
* AcceptedCmp3: 1 if customer accepted the offer in the 3rd campaign, 0 otherwise
* AcceptedCmp4: 1 if customer accepted the offer in the 4th campaign, 0 otherwise
* AcceptedCmp5: 1 if customer accepted the offer in the 5th campaign, 0 otherwise
* Response: 1 if customer accepted the offer in the last campaign, 0 otherwise

#### Place

* NumWebPurchases: Number of purchases made through the company’s website
* NumCatalogPurchases: Number of purchases made using a catalogue
* NumStorePurchases: Number of purchases made directly in stores
* NumWebVisitsMonth: Number of visits to company’s website in the last month

### Data Wrangling and Cleaning

* check and convert data type
* input missing data
* check and remove outliers
* check duplication
* values in categorical columns: gorup abnormal values into other value 
* combine/drop/create columns
* encode non-numeric columns
* scale the dataset

### Data Storage

* `.csv` file.

## Data Analysis

### EDA
* Understanding of data
* Correlation
* Descriptive Analysis


### Model Training and Evaluation
	* PCA
	* Model Building 
	* Model Evaluation
	* Unsupervised ML

## Conclusion
* Insight of clusters
* Patterns Analysis from Descrptive Statistics
* Profiling

![clusters profile](https://user-images.githubusercontent.com/93996718/153616643-19fe1290-3e7a-42e7-b18d-be66e2dc90ad.jpg)
