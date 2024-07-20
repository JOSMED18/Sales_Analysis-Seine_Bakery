# Sales Analysis: Seine Bakery Shop
![image](https://github.com/user-attachments/assets/99630ffd-fd53-4005-95f1-8508249a3757)

This workbook show an approach of the ABC sales analysis based on the Pareto principle as well as some time intelligence approaches. See the online version by clicking in the link below: https://1drv.ms/x/s!AhhtE9eDv1mKzmspoqA0ocb3rdb7?e=daBg7J

## Insights
### ABC Analysis
![image](https://github.com/user-attachments/assets/85234c0c-3fd9-4678-9cd7-4606f9a694c0)
The ABC and Pareto analysis states that 80% of income or revenue comes from the 20% of the products portfolio, those are products A. It is followed by products B which earns 15% of the total income, and products C the 5%. In this case, the pareto chart shows that 79.70% of income comes from 16.9% of the products! That's even less than 20%. In the other hand, the products C make a contribution of 5.10% for the total income and it is composed of about 61.3% of the products. This would be a good start to check which products are underperforming and take decision: take it off or create a new strategy to increase sales for one of those products (it can also be a product with seasonality, sold only in January for example).

### Orders by day of the week
![image](https://github.com/user-attachments/assets/c7cdacae-a7df-4ea0-b451-70c25f9f59d0)
This chart shows the distribution of orders through the week. Due to the type of business, it is normal to have a bigger traffic and sales on weekends. Demand should stay partially constant during the week from monday to friday, and it is. However, for wednesdays demand is usually down so it is a focus point on the marketing strategy. There are some strategies that can be performed on this case. Some big malls set buy 1 and get 2 offers on monday for coffee shops due to the low traffic and demand for example. It could be a great option for this day. A great approach would be looking at the most sold pair of products and set an offer for that specific day.

### Orders by month and year
![image](https://github.com/user-attachments/assets/aa321357-1b45-4d69-ae3a-ca69d00ab445)
Since the data is available for at least one and a half year, we can spot a seasonality on the months with at least 2 cycles (i.e. January to August). This is a great insight in terms of supply chain managements since the resource planning and manufacturing can be planned in advance. For instance, let's take a look at july and august: they have shown the highest sales on 2021 and 2022, so it is a good idea for 2023 to plan the purchase of raw materials at least one month in advance to avoid inventory shortage at that time and lose sales. Also, it is good to review the available human resources at hand, do we have enough capacity for this two months?

We can also look at the lowest points in the year and one of the most curious: february. Due to the type of business, this month should be a great opportunity to increase sales since Valentine's day is celebrated the 14th of february. A great season to make offers for couples and friends, prepare special cakes and breads, even increase sales on _A_ products

### Data Modelling
The data model was built in Microsoft Excel using Power Pivot which offers a view as if you were working through Microsoft Power BI. The data was cleaned using formulas instead of the integrated query editor. For some measures MDX language (similar to DAX in Power BI) was used. 
![image](https://github.com/user-attachments/assets/4d524954-69e8-4f4f-a75f-78348021e848)
