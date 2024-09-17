
Project Overview
Business Problems and Challenges
In today's competitive business environment, identifying and prioritizing high-value customers who significantly contribute to revenue is a complex task. This complexity is compounded by a diverse customer base, requiring sophisticated analytical tools to discern patterns. Additionally, high customer churn rates and the lack of personalized customer experiences further impede business growth.
Business Objectives
Our project seeks to address these challenges using the RFM (Recency, Frequency, Monetary) model. We aim to:
1.	Identify and focus on high-value customers.
2.	Create personalized shopping experiences based on RFM segments.
3.	Revise retail policies to attract and retain customers with low purchasing frequency.
Key Business Questions
1.	How can we increase repeat purchases from high-value customer groups in the next three months?
2.	How can we personalize customer experiences based on RFM segments?
3.	What behavioral characteristics of current customers are applicable to new markets?
Data Preparation
Data Collection
We collected historical sales transaction data from April 29, 2023, to April 28, 2024, encompassing comprehensive details from the Sales and Marketing Departments. This dataset includes customer-specific data, product details, and transaction records.
Data Description
The dataset comprises 100,000 rows and 10 columns, with variables such as CustomerID, ProductID, Quantity, Price, TransactionDate, PaymentMethod, StoreLocation, ProductCategory, DiscountApplied (%), and TotalAmount.
Data Cleaning and Preprocessing
Data cleaning involved handling missing values, removing duplicates, and standardizing formats. We used methods like Box-Cox transformation and z-score scaling for data normalization and preparation for clustering analysis.
Methodology
RFM Calculation
We calculated the Recency, Frequency, and Monetary values for each customer. The dataset was normalized and scaled to ensure suitability for clustering analysis.
Clustering
Using the Elbow method and Silhouette analysis, we determined that four clusters were optimal. The K-means clustering algorithm was then applied to segment the customers based on their RFM scores.
Cluster Labeling and Analysis
We labeled the clusters as follows:
•	Cluster 0: VIP Customers - Most recent purchases, highest frequency, and highest spending.
•	Cluster 1: Infrequent Customers - Least frequent purchases and lowest spending.
•	Cluster 2: Potential Customers - High spending but less frequent.
•	Cluster 3: General Customers - Moderate recency and spending.
Each cluster was analyzed to gain insights into customer behavior and value.
Results and Discussion
Visualization and Data Storytelling
We created comprehensive dashboards to visualize the data and clustering results. Key findings include balanced sales distribution across clusters and product categories, and identification of high-value, potential, general, and infrequent customers. Recommendations were made for targeted marketing strategies to enhance engagement and retention.
Customer Lifetime Value (CLV) Prediction
CLV prediction was performed to forecast the potential value of customers over time, aiding in strategic decision-making for customer retention and growth.
Cohort Analysis
Cohort analysis was conducted to visualize customer retention rates over time, providing insights into customer loyalty and engagement patterns.
Conclusion and Future Directions
This project successfully employed the RFM model and K-means clustering to segment retail customers, offering actionable insights for business strategy. Future work will focus on refining the models, exploring additional data sources, and implementing personalized marketing campaigns based on these findings.
Acknowledgments
We extend our sincere gratitude to Assoc. Prof. Ho Trung Thanh, Ph.D., for his invaluable guidance and support throughout this project. His expertise and dedication were crucial to our success.

