# Amazon_Vine_Analysis

## Overview
SellBy is an e-commerce company, they are looking to launch a new line of products. Their stakeholders want to know if they should enroll in the Amazon Vine Program. Retailers pay Amazon to receive published reviews from Vine members. Most importantly, the decision will come down to determining whether the Vine program is biased toward favorable reviews.

I've downloaded a big dataset containing technology product reviews from Amazon. With Pyspark, I was able to extract, transform, and load 10,000 rows of data into PostgreSQL using AWS Relational Database Service.


## Results
Number of Vine reviews and non-Vine reviews
![ava1](https://user-images.githubusercontent.com/106359564/224214575-5d290bc9-5487-46fc-acd3-f4e5882bfbd7.png)


Number of 5-star rating reviews from Vine reviews and non-Vine reviews
![ava2](https://user-images.githubusercontent.com/106359564/224214582-f39014c0-aff8-48a9-960f-ea30cf63d61a.png)


Percentage of 5-star rating reviews from Vine reviews and  non-Vine reviews
![ava3](https://user-images.githubusercontent.com/106359564/224214588-a242603b-363e-4720-bbdd-6dc0984fd0a1.png)



## Summary
With PySpark, I was able to analyze the ratings and determine that the Vine reviews were not biased toward 5-star ratings. The amount of unpaid 5-star reviews was actually 2% higher than paid reviews through the Amazon Vine Program. 

For additional analysis, we could compare these reviews to other product categories. It would also be helpful to find a dataset where the number of vine reviews is closer to the number of unpaid reviews to see if bias ratings become significant.
