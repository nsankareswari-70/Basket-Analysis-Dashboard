# Basket-Analysis-Dashboard

## What is Basket Analysis?
A basket analysis is a data mining technique used by retailers to identify relationships between items that are frequently purchased together in transactions, revealing customer purchasing patterns to increase sales and profits. By analyzing past purchase data, businesses can understand which products are often bought in the same "basket," then use these insights for strategies like store layout optimization, personalized promotions, and product bundling to influence customer behavior and boost revenue.

There are 3 key concepts in basket analysis
1.	Support - Indicates the frequency of the products being bought together
2.	Confidence - Indicates the direction for cross selling
3.	Lift - Indicates the strength of the relationship between the products

Support = Number of Transactions including both Products / Total number of transactions

Confidence of Product one = Support of Basket / Support of product one


Confidence of Product Two = Support of Basket / Support of Product two

Lift = Support of basket / (Support of Product one * Support of Product two)



## In this project, I have used Drill Down Network PRO - (By zoomcharts)

About Drill Down Network PRO - chart: 
Create beautiful, easy to explore networks from category-based data and add them straight to your dashboard. This chart automatically detects relations among categories, its force feedback layout prevents nodes from overlapping, and rich customization options let you control the look of each category. 

Drill Down Network PRO (Pin) by ZoomCharts

![img alt](https://github.com/nsankareswari-70/Basket-Analysis-Dashboard/blob/baaf534b9896600707371df62250b7610ed0dd32/BasketAnalysis1.png)

![img alt](https://github.com/nsankareswari-70/Basket-Analysis-Dashboard/blob/5e21c4bd4af17120dc6e40ab530b40d75c373f38/BasketAnalysis2.png)

The first image shows products bought together with Butter.
The second image shows products that are bought together with Yogurt.

![img alt](https://github.com/nsankareswari-70/Basket-Analysis-Dashboard/blob/0ee8560410376e116a028d6eb8b4192e8c84a6fb/BasketAnalysis3.png)

