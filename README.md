# Customer-Segmentation
### Project Objective
Object of the project is to give useful insights about customer and also to Segment the customer based on their purchasing behavior to improve Store revenue. We will train the model using KMeans clustering, unsupervised Machine learning algorithm as we need to segment the customer as per their purchasing behavior.
### Data Source
Customer Data- Primary data source used here is "OnlineRetail.csv" file containing the detailed information about each Customer.
### Data Description
This is a transactional data set which contains all the transactions occurring for a UK-based online retail store.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.
The online_retail.csv contains 387961 rows and 8 columns
### Tools
 - Pandas for Data Cleaning,Preparation,Outlier analysis,EDA.
 - Unsupervised Machine Learning algorithms from Sklearn.
### Inferences
- RFM analysis is used to organize customer databases into specific segments. Depending on these segments, customer’s purchase behavior gave crucial insight 
  into the type of marketing which should be used to target them and to move them between segments.
- Frequency and monetary values are core to calculating the customer purchasing power, meanwhile,  recency gives insight into customer engagement and indicates the likelihood of that customer coming back again.
- Customers of Cluster 1 are most frequent buyers business needs to give importance to these customers to improve their sales. 
- Customers of Cluster 2 did most recent transactions where as Customers with Cluster Id 0 are not recent buyers and hence least of importance from business point of view.
### Future Possibilities of the Project
Best customer(high R/high F/high M): this customer segmentation shows customer has high loyalty, who visit the retail store most recent, high frequently purchased and have purchased with high amount of goods, therefore this segmentation is the best customer who brings the highest value to the company. "Recency" shows customer from this segmentation purchase 1-2 months ago before December with monetary amount of 1300-2200£, so the online store could start to prepare and send marketing information to customer before October to increase customer's attention, the company should give most of the marketing budget to this segmentation. The company could launch new product information through email marketing for promotion, provide VIP service to increase customer satisfaction, send customer questionnaires to know the need of specific product and prepare enough stock. Furthermore, can trace back the CustomerID in order to know this customer segmentation's demographic, geographic,psychography,etc, information to predict the customer buying behavior, and combine with "frequency" and "Monetary" data to predict customer life cycle in this segmentation. The company  should mainly focus on how to increase customer stickiness and customer loyalty and customer satisfaction of Cluster0 customer, understand different sub-segmentation of cluster2 customer and create personalized marketing strategy for transferring it to the best customer segmentation, and reduce/withdrawal budget for Cluster0 customers.
