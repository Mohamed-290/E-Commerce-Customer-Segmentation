# E-Commerce-Customer-Segmentation :

Dataset Overview:  You will be working with a dataset consisting of five interrelated tables, each containing crucial  information about customers, transactions, branches, and merchants. The tables are described 
as follows: 

1. Customers Table: 
○-- >customer_id: Unique identifier for each customer. 
○--> join_date: The date the customer joined. 
○--> city_id: The ID representing the customer's city. 
○--> gender_id: The ID representing the customer's gender.

2. Genders Table: 
○--> gender_id: Unique identifier for each gender. 
○--> gender_name: Name of the gender (e.g., male, female).

3. Cities Table: 
○--> city_id: Unique identifier for each city. 
○--> city_name: Name of the city.

4. Transactions Table: 
○--> transaction_id: Unique identifier for each coupon transaction. 
○--> customer_id: ID of the customer who performed the transaction. 
○--> transaction_date: The date the coupon was claimed. 
○--> transaction_status: Status of the coupon (e.g., claimed, burnt).
○--> coupon_name: The name of the coupon. 
○--> burn_date: The date the coupon was burnt. 
○--> branch_id: ID of the branch where the coupon was burnt.

5. Branches Table: 
○--> branch_id: Unique identifier for each branch. 
○--> merchant_id: ID of the merchant who owns the branch.

6. Merchants Table: 
○--> merchant_id: Unique identifier for each merchant. 
○--> merchant_name: Name of the merchant.

-----------------------------------------------------------------------------------------------------------------------------

# Customer Segmentation Using Unsupervised Learning :

The second part of the task requires you to develop and train an unsupervised machine learning 
model to segment customers based on their transactional behavior and other relevant features 
from the dataset. The goal is to identify customer groups that share similar behaviors and use 
these segments to discuss strategies for offering coupons to increase loyalty and satisfaction. 

## Key instructions: 

1. Feature Selection: Utilize customer demographic features (e.g., gender, city) and 
transactional features (e.g., coupon usage frequency, transaction status) for 
segmentation.

3. Model Development: 
● Train and evaluate an unsupervised machine learning model (such as K-Means clustering) for customer segmentation. 
● Ensure to explore different numbers of segments (clusters) and optimize your model 
for meaningful customer groups.

5. Model Evaluation: Use appropriate evaluation metrics for unsupervised learning, such as:  
● Inertia (for K-Means). 
  

6. Segment Analysis:
   Analyze and describe each segment based on customer behavior, and make recommendations on which segments should be given coupons to maximize their 
loyalty and satisfaction with the store.
