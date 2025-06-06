 Objective

The goal of this project is to perform customer segmentation using the **K-Means Clustering** algorithm. By analyzing mall customer data, we aim to group customers based on their **Annual Income** and **Spending Score**, helping businesses to understand different customer profiles for targeted marketing.



Dataset Information

**Filename:** 

Technologies Used

- Python 
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn (sklearn)



 Steps Performed

1. **Data Loading and Exploration**
   - Loaded the dataset using pandas.
   - Viewed the first few rows and checked for missing values.

2. **Feature Selection**
   - Selected `Annual Income (k$)` and `Spending Score (1-100)` as the features for clustering.

3. **Data Visualization**
   - Created scatter plots to visualize customer distribution.

4. **Elbow Method**
   - Used the Elbow Method to determine the optimal number of clusters (`k`) based on Within-Cluster Sum of Squares (WCSS).

5. **Apply K-Means Clustering**
   - Applied the K-Means algorithm with the optimal number of clusters (e.g., k=5).
   - Predicted cluster labels for all data points.

6. **Cluster Visualization**
   - Visualized the resulting clusters along with their centroids.


Output

- Identified 5 distinct customer segments.
- Gained insights into which customers are high spenders, low-income, or potential targets.


Visualization Example

- A scatter plot showing customer clusters.
- Centroids shown in yellow.



