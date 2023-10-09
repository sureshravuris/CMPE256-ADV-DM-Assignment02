# CMPE256-ADV-DM-Assignment02

# **Starbucks Hot Beverages Cluster**

## **Overview**
This repository provides a data-driven approach to segment Starbucks customers based on their purchasing behaviors during different times of the day. By understanding these segments, the Starbucks store manager can offer targeted promotions to enhance customer loyalty and boost sales.

## **Data**
The dataset contains sales data of hot beverages at popular times on a typical Wednesday.

- **PTIndex:** Popular times index, ranging from 1 (6am-7am) to 11 (8pm-9pm).
- **HBIndex:** Hot Beverages index, ranging from 1 (Coffee type 1) to 9 (Coffee Of the Day).

## **Methodology**
1. **Data Visualization:** Initial visualization of the dataset to understand the distribution of beverage sales across popular times.
2. **KMeans Clustering:**
- Use the Elbow method to determine the optimal number of clusters.
- Apply KMeans clustering to segment the data.
3. **Hierarchical Clustering:**
- Visualize dendrograms for Single Linkage, Complete Linkage, and Average Linkage.
- Apply hierarchical clustering for each linkage method and visualize the resulting clusters.
4. **Recommendations Generation:** Based on the clusters formed, generate targeted promotions to cater to each customer segment.

## **Results**
-> KMeans: Three distinct customer segments were identified, each representing different purchasing behaviors at various times of the day.

**1. Single Linkage:** Produced one dominant cluster with a few outliers, suggesting a broad customer behavior with minor variations.

**2. Complete Linkage:** Yielded distinct and balanced clusters, providing clear insights into varied customer behaviors.

**3. Average Linkage:** Offered a balanced perspective with clusters representing slightly different behaviors compared to Complete Linkage.

## **Recommendations**
Based on the clusters formed, targeted promotions can be introduced:
- Morning discounts for early bird customers.
- Afternoon combo offers to boost sales during the typical slump.
- Evening specials for late-day customers.
  
## **Usage**
- Visualize the raw dataset.
- Determine the optimal number of clusters using the Elbow method.
- Apply KMeans clustering and visualize the clusters.
- Apply hierarchical clustering (Single, Complete, Average) and visualize the dendrograms and clusters.
- Generate targeted promotion recommendations based on the clusters.
   
## **Future Work**
- Collect post-promotion data to measure the effectiveness of the targeted offers.
- Iteratively refine the clustering and promotional strategies based on new data.
