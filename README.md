# E-commerce-Customer-Segmentation
# Abstract:
A key challenge for e-commerce businesses is to analyze the trend in the
market to increase their sales. The trend can be easily observed if the
companies can group the customers; based on their activity on the ecommerce
site. This grouping can be done by applying different criteria like
previous orders, mostly searched brands and so on.
# Problem Statement:
Given the e-commerce data, use k-means clustering algorithm to cluster
customers with similar interest.
# Dataset Information:
The data was collected from a well known e-commerce website over a
period of time based on the customer’s search profile.
# Variable Description:
Column_Description
- Cust_ID--Unique numbering for customers
- Gender--Gender of the customer
- Orders--Number of orders placed by each customer in the past
----------------------------------------------------
Remaining 35 features (brands) contains the number of times
customers have searched them
# Scope:
- Analyzing the existing customer data and getting valuable insights
about the purchase pattern
- Data pre-processing including missing value treatment
- Segmenting customer based on the optimum number of clusters (‘k’)
with the help of silhouette score
# Learning Outcome:
The students will get a better understanding of how the variables are
linked to each other and will be able to apply cluster analysis to business
problem such as customer segmentation.

----------------------------------------------------
# Workflow
- Importing required libraries like pandas, numpy, matplotlib, plotly, sklearn-cluster kmeans,silhouette_score,KElbowVisualizer
- performing required EDA i.e filling nullvalues in Gender
- understating something about dataset and make strategies to make targets.
- as per problem statement used Silhouette analysis For Optimal k
- But using Elbow Graph and Elbow Visualizer k value for cluster is decided
- now making new target as grouping customers under various criterias below
- grouping the customers by number of orders
- grouping the customers by mostly searched brands
- grouping customers with number of orders and total searches
- finally giving conclusion for each strategy/criteria.
# Demo:
[check out the linkedin post for demo video](https://www.linkedin.com/posts/kalin-harikumar-230349140_project-guvi-ecommerceabrcustomerabrsegmentation-activity-7064665802444046337-U63h?utm_source=share&utm_medium=member_desktop)
