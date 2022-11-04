# E-Commerce-Shipping-Data
shipment of products delivered on time or not? To fulfill e-commerce customer Demand

### Problem Statement
Parcel Perform is a software-as-a-service (SaaS) package capable of tracking more than 600 logistics operators globally. Parcel Perform found that there were more than 90 percent of complaints and negative responses from customers related to late delivery. The survey shows 35 percent of customers continue to view shipping as the biggest problem in e-commerce. Optimizing the delivery experience is crucial to increasing the benefits that customers receive because customer satisfaction is the key to customer loyalty. Therefore, the company needs to improve goods delivery services.

Problem:
An international e-commerce company based wants to discover key insights from their customer database. They want to use some of the most advanced machine learning techniques to study their customers. This company sells electronic products.

Objective: 
Build a model to predict whether ordered products are delivered on time or not

### Data Description
Source: https://www.kaggle.com/datasets/prachi13/customer-analytics
The dataset used for model building contained 10999 observations of 12 variables.
The data contains the following information:

ID: ID Number of Customers.
Warehouse block: The Company have big Warehouse which is divided in to block such as A,B,C,D,E.
Mode of shipment:The Company Ships the products in multiple way such as Ship, Flight and Road.
Customer care calls: The number of calls made from enquiry for enquiry of the shipment.
Customer rating: The company has rated from every customer. 1 is the lowest (Worst), 5 is the highest (Best).
Cost of the product: Cost of the Product in US Dollars.
Prior purchases: The Number of Prior Purchase.
Product importance: The company has categorized the product in the various parameter such as low, medium, high.
Gender: Male and Female.
Discount offered: Discount offered on that specific product.
Weight in gms: It is the weight in grams.
Reached on time: It is the target variable, where 1 Indicates that the product has NOT reached on time and 0 indicates it has reached on time.


This data of Product Shipment Tracking, answer instantly to your questions:
Question 1 : Find which features has high contribution 
Discount_offered with positive correlation

Question 2 : Find the best model to predict on-time shipment reach
Decision tree has the highest recall score compared to other models, which is 70%

Question 3: Find the factors that make product shipment on time
- A large discount (>14%) can cause the number of sales to increase, so that the shipment volume increases and causes delay shipments
- Likewise with cost_of_the_product, the more expensive the product sold, the higher the possibility of delivery on time
- Low and medium importance products actually experience on-time delivery
- Shipments by road and block F tend to be on time
- Make a call to the seller at least 2 times
- Shipment of products weighing > 4kg tends to be on time


