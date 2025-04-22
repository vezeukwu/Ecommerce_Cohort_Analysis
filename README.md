# Introduction

E-shop Pro is a leading e-commerce company with lots of products and services specially formulated for its customers. They are known for their commitment to quality and excellent customer service, which in turn breeds customer satisfaction. Some of its major achievements are: Growth in its user base by 30% annually over the last five years, Implementation of a personalized recommendation system, improvement in customer satisfaction, and achieving an 80% retention rate among VIP customers in the first two years of loyalty program implementation. In spite of this, E-sho Pro is facing a significant challenge in retaining its customers, evident in the alarmingly high shopping cart abandonment rate.

I delved into Cohort Analysis to gain a deeper understanding of customer behavior. This analytical approach enabled me to segment E-shop Pro customers into cohorts based on their purchase behavior over time, which was instrumental in identifying key retention opportunities and optimizing marketing efforts. By analyzing these cohorts, I developed strategies that helped businesses improve customer engagement and increase the effectiveness of their marketing campaigns.


# Tools and Libraries Used:
Python - Programming Language  
Numpy - For performing mathematical operations over data
Pandas - for data analysis and manipulation
Seaborn and Matplotlib - for data visualization
Scikit-learn - for machine learning


# Data Description 
The dataset required for this project will include:
- InvoiceNo: A unique identifier for each invoice or transaction, often used for tracking and reference purposes.
- StockCode: A code or identifier associated with a specific product or item in the e-commerce store's inventory, used for cataloging and tracking purposes.
- Description: A categorical feature providing a brief textual description of the product being sold, offering clarity to customers about what they are purchasing.
- Quantity: The quantity or number of units of a product included in the transaction that indicates the purchase volume for each item.
- InvoiceDate: The date and time when the transaction or invoice was generated, offering insights into when purchases were made and allowing for temporal
analysis.
- UnitPrice: Indicating the total cost of the items purchased.
- CustomerID: A unique identifier associated with each customer or shopper, allowing for customer-specific analysis and tracking of individual purchasing behavior.
- Country: The name of the country where the customer is located or where the transaction occurred.

# Exploratory Data Analysis
I embarked on exploratory data analysis to uncover trends and patterns, exploring countries with the highest customers, top-selling products sold per country each month. 

The sales trend shows revenue increased consistently across all quarters with its peak in the 4th quarter of 2011.

2010 Q4 to 2011 Q1: A sharp increase in sales quantity noted. 2011 Q1 to 2011 Q3: A steady increase occurred. 2011 Q3 to 2011 Q4: Sales experienced a further sharp increase.

![Screenshot 2025-04-22 095529](https://github.com/user-attachments/assets/018fdef5-c356-4219-add0-59d90136ae8b)


Investigating top selling products through the months, jewelry sold most in November, cosmetics sold more in October, kitchenware in August etc.

![Screenshot 2025-04-22 095427](https://github.com/user-attachments/assets/75358667-cb89-4fa4-90d1-2d9b2b8eb450)


# Cohort Analysis
Using cohort analysis I segmented users into distinct groups, or cohorts, based on certain criteria. These cohorts were defined by the time of user acquisition. By grouping users based on time of acquisition, we saw how different cohorts behave in terms of engagement and retention. 

A healthy retention rate for e-commerce platforms is typically considered to be in the range of 20% to 40%. This means that 20% to 40% of E-shop Pro customers continued to make purchases from the e-commerce platform after their initial purchase.

![Screenshot 2025-04-22 095221](https://github.com/user-attachments/assets/d32ed5fc-a803-4e35-8e67-efcc50731f95)


December 2010 Cohort Outperforms Others: The fact that the December 2010 cohort has a retention rate above 30% is a positive sign. It suggests that this group of customers has remained engaged with your e-commerce platform over time. This could be due to various factors, such as the quality of your products/services, effective marketing, or a strong customer retention strategy.

Decline in December 2011: The observation that all cohorts have low retention rates in December 2011 suggests that there may have been specific challenges or issues affecting customer retention during that time. It's important to investigate what might have caused this decline and whether it's a one-time event or a recurring pattern

Variability in Retention Rates: The range of retention rates, from a minimum of 8% to a maximum of 50%, suggests that there is significant variability in how different cohorts of customers are behaving. While 8% is relatively low, 50% is relatively high, considering the standard e-commerce retention rates mentioned earlier.

# RECOMMENDATIONS
Identify Factors Driving High Retention (December 2010): E-shop Pro to analyze what factors have contributed to the high retention rate for the December 2010 cohort. Was there a specific marketing campaign, product improvement, or customer engagement strategy that worked well for this group? Try to replicate successful strategies for other cohorts.

Investigate December 2011 Drop: Investigate why all cohorts have low retention rates on December 2011. It might involve analyzing customer feedback, product quality, customer service, or any changes in your business operations during that time. Identifying and addressing the root causes of this drop is crucial for improving future retention rates.

Set Realistic Targets: While the standard e-commerce retention rate range is 20% to 40%, it's essential to set targets that are specific to your business and its circumstances. Aim to improve retention rates gradually over time based on your historical data and industry benchmarks.

Implement Retention Strategies: Develop and implement retention strategies that are tailored to different cohorts of customers. Personalized marketing, loyalty programs, and targeted communication can help improve retention rates.

Continuously Monitor and Adapt: Retention rates can change over time due to various factors, so it's crucial to continuously monitor them and adapt your strategies accordingly. Regularly analyzing cohort data and customer behavior will help you make informed decisions to improve retention.

In addtion to observing the behaviour of each cohort, we can create a table which shows the average quantity of product bought by each cohort and how it fluctuates.
