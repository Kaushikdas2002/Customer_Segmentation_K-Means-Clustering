# Customer_Segmentation_K-Means-Clustering

## Introduction
Customer segmentation is a crucial marketing strategy that involves dividing a customer base into distinct groups that share similar characteristics. This project utilizes the K-means clustering algorithm to segment customers based on their purchasing behavior using the Mall Customer dataset.  

## Data
The dataset used for this project is the Mall Customer dataset, which typically contains the following columns:
1. CustomerID  
2. Gender  
3. Age  
4. Annual Income (k$)  
5. Spending Score (1-100)

## Steps
1. **Data Preprocessing**  
-**Load the Dataset**: Read the customer data CSV file into a DataFrame.  
-**Handle Missing Values**: Ensure there are no missing values in the dataset.  
-**Save Cleaned Data**: Store the preprocessed data for further analysis.  

2. **Determine Optimal Number of Clusters**  
-**Elbow Method**: Plot the sum of squared distances from each point to its assigned cluster center and look for the "elbow" point where the curve bends.  

3. **Apply K-Means clustering**  
-**Fit the Model**: Apply the K-means algorithm to the preprocessed data using the optimal number of clusters.    

4. **Visualization**  
-**Visualize Clusters**: Create scatter plots and other visualizations to observe the distribution of customers across different clusters based on key features like Age, Annual Income, and Spending Score.

## Outcomes
1. **Clustered Data**:
Each customer will be assigned to a cluster.  

2. **Optimal Number of Clusters**:
A plot showing the Elbow method to determine the optimal number of clusters.  

3. **Visualizations**:
Scatter plots and other visualizations showing the distribution of customers across different clusters based on key features like Age, Annual Income, and Spending Score.  
