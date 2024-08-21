# Customer-Segmentation-with-ML


Used KNN and DBSCAN algorithm to do the customer segmentation. Added some Visualization reports as well. 


🚀 Project Spotlight: Market Segmentation in Insurance using Unsupervised Machine Learning 🚀

I recently completed an exciting project that focused on leveraging unsupervised machine learning techniques for market segmentation in the insurance industry. The goal was to identify distinct customer segments based on their purchasing behaviors and credit usage, allowing for more targeted marketing strategies and improved customer satisfaction.

Project Overview:
🔍 Data Used: Customer transactional data with 8,950 entries and 18 features.
🔧 Techniques Employed:
- K-Means Clustering: Utilized to partition customers into distinct groups based on their similarities in purchasing behaviors.
- Agglomerative Clustering: Applied to further refine and validate the segments by considering the hierarchical relationships between data points.

Steps Taken:
1. Data Cleaning & Preprocessing:
 - Handled missing values by imputing with mean values.
 - Dropped non-informative columns like CUST_ID.
 - Identified and classified features into discrete and continuous categories.
 
2. Exploratory Data Analysis (EDA):
 - Visualized the distribution of features like TENURE and PURCHASES.
 - Identified trends and patterns that guided the clustering approach.
 
3. Clustering Implementation:
 - K-Means Clustering: After running multiple iterations, I found the optimal number of clusters using the Elbow method and silhouette scores.
 - Results: The data was grouped into 2 distinct clusters with silhouette scores indicating clear separation between segments.
 - Agglomerative Clustering: Confirmed and fine-tuned the clusters obtained from K-Means by analyzing the dendrogram and choosing an appropriate cut-off.
 - Results: The clusters were validated, providing further insights into the hierarchical structure of customer segments.

Key Insights:
- Customers were segmented into distinct groups based on their spending habits, frequency of purchases, and credit usage.
- The segmentation revealed actionable insights, such as identifying high-value customers who could be targeted with premium insurance products.

Results:
📈 Silhouette Score for K-Means Clustering: 0.404
📉 Agglomerative Clustering Cophenetic Correlation Coefficient: 0.324

Outcome:
This project underscored the power of unsupervised learning in extracting valuable insights from complex datasets. By effectively segmenting the customer base, insurance companies can now tailor their products and services to meet the specific needs of different customer segments, ultimately driving higher customer satisfaction and business growth.

Looking forward to applying these insights in real-world scenarios and continuing to explore the fascinating world of data science! 💡

hashtag#MachineLearning hashtag#DataScience hashtag#Insurance hashtag#MarketSegmentation hashtag#Clustering hashtag#UnsupervisedLearning hashtag#KMeans hashtag#AgglomerativeClustering
