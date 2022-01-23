# Segmentation-in-R
## Introduction

Data segmentation is an extremely useful analysis, among others in the area of marketing and sales. It is a division of customers according to strictly defined criteria, which aims to define the main groups of recipients of products. Groups with similar needs, interests or shopping preferences. Segmentation is used in adapting services to market needs, increasing the effectiveness of a marketing campaign and, as a result, increasing profits. The main idea of the project was the practical application of models for assessing the value of customer relationships.

The conducted analysis aims to:
- determining the number of customer segments in the store
- determining how big each segment is by determining its share of the population
- defining the characteristics of the customers of the store in a given segment

## Dataset

The following project uses data from the kaggle.com platform - https://www.kaggle.com/vjchoudhary7/customer-segmentation-tutorial-in-python?select=Mall_Customers.csv, regarding the customers of the shopping center, collected with the help of loyalty cards. Set contains 200 observations and the following 5 variables:
- CustomerID - customer identification number
- Gender - client's gender
- Age - age
- Annual_Income - annual income (in thousand)
- Spending_Score - customer spending index in the store on a scale from 1 to 100

## Summary

1. The purpose of the market analysis was segmentation
customers. Segmentation was performed using the K-means method.
2. In the first step, an exploratory analysis of the data used to build the segmentation model was performed. The dataset used had
5 variables. During data processing and cleaning, two variables were removed, of which three others were used for segmentation, i.e. Age, Annual Income and Spending_Score. Correlation heatmaps of continuous variables were created to investigate the relationships between the variables, and then the distributions of the continuous variables were examined. The collection was normalized with the Z-score method.
Despite the slight asymmetry of the distributions, the normalization made it possible to reduce all variables to a comparable scale.
3. The segmentation model was created using the K-means method. 5 clusters were obtained, i.e. 5 considered customer groups:
- Older, low-wage earners below average spending
- Adults, with very high wages, but spending sparingly
- The youngest customers, spending a lot in relation to their earnings
- Middle-aged shoppers with moderate wages and expenses
- Young adults with high wages and expenses
4. The results of segmentation of the store's customers allow the owners to assess which group of customers should be focused on in order to maximize profits. In the analyzed example, the most numerous group are middle-aged customers who earn and spend moderately, so they should certainly take into account people with such a profile when creating a strategy or marketing campaign. Additionally, it should be noted that the two least numerous groups include people who spend little, and the next one includes the youngest customers (average 22 years). For this reason, owners should consider increasing the percentage of people with such characteristics by adjusting their offer to such people. Perhaps the store does not meet the requirements of people who choose small, spontaneous shopping, because a small shopping basket is characterized by a small group. What's more, young people are also more likely to choose competition. Targeting these people could help increase your turnover by attracting new customer groups.
5. The 3D charts made it possible to visually assess the number and vicinity of the clusters.

