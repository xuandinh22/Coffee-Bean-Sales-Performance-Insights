# Coffee Bean Sales: Performance Insights
## Background and Overview
The Coffee Bean Sales dataset provides a detailed view of customer transactions, loyalty participation, and product preferences across US, UK, and Ireland. This project applies Excel and Tableau to explore how customer loyalty, product type, and geography influence overall sales performance. The analysis aims to uncover opportunities for improving retention and better align product offerings with customer preferences.

<img width="25" height="25" alt="image" src="https://github.com/user-attachments/assets/c7fd2787-3b30-4b70-a5d7-fb1947851fb3" />
Hypothetical Business Situation: 
“Brew & Bean” is a small coffee bean branch operating in the US, UK, and Ireland. Over the past four years (2018 to 2022), the brand has collected detailed data on customer purchases, product types, and loyalty program participation. In 2022, the business began showing signs of decline, prompting the management team to seek a deeper understanding of sales performance to make informed decisions regarding customer retention, product offerings, and market expansion.  

####  
The shop faces several key questions:

•	Does the loyalty card program help with customer retention and boost sales?

•	Which coffee types, roasts, and pack sizes are the most popular and profitable, and are there opportunities to optimize inventory or promotions?

•	How do sales differ across countries and cities, and which markets show the greatest potential for growth?

The management hopes that a comprehensive analysis of historical sales data will uncover actionable insights to strengthen the business, enhance customer engagement, and guide strategic decisions.


<img width="21" height="21" alt="image" src="https://github.com/user-attachments/assets/12111bef-782c-47cd-ba3a-311b55dc679b" />
 Insights and recommendations are provided on the following key areas:

 ####  
•	Customer Loyalty: Comparing loyalty card holders with non-members in terms of sales volume, profit, purchase frequency, and repeat behavior.

•	Product Type: Identifying which coffee type, roast, and size combinations drive the highest sales and profit.

•	Geography: Evaluating sales performance by country and city to highlight the strongest markets and customer preferences.

<img width="23" height="23" alt="image" src="https://github.com/user-attachments/assets/3d8baa56-2f39-452e-9edf-2efc99427de3" />
Tools:

####  
• Excel (Power Pivot): Data cleaning, preparation, and analysis

• Tableau: Interactive dashboard creation and visualization

• Draw.io: The initial dashboard mockup

• Flaticon: Icon sourcing for dashboard visuals

• Paint: Icon customization and editing

Data Source: <a href="https://www.kaggle.com/datasets/saadharoon27/coffee-bean-sales-raw-dataset">Coffee Bean Sales Raw Dataset</a>.

An Interactive Tableau dashboard can be downloaded <a href="https://public.tableau.com/app/profile/xuan.dinh8619/viz/CoffeeBean_17562288415120/Dashboard3?publish=yes">here</a>.

The Excel file containing the data cleaning, preparation, and analysis work is available <a href="https://github.com/xuandinh22/Coffee-Bean-Sales-Performance-Insights/blob/main/Coffee%20Bean%20Project.xlsm">here</a>.

The initial dashboard mockup can be found  <a href="https://github.com/xuandinh22/Coffee-Bean-Sales-Performance-Insights/blob/main/Dashboard%20Mockup.pdf">here</a>.

## Data Structure Overview
The dataset consists of three tables, providing information on coffee bean Products, customer Orders, and Customer profiles.
<p align="center">
<img width="600" height="400" alt="Tables" src="https://github.com/user-attachments/assets/84f0e2ae-c2b0-4d63-b65b-6b4350e5e871" />
</p>

## Executive Summary
### Overview of Findings
The number of orders rose steadily from 2019 to 2020, peaked in 2021, and then declined in 2022. However, the total quantity sold followed a slightly different pattern. Despite more orders were placed in 2020 than in 2019, the quantity sold slightly decreased. Sales volume reached its highest level in 2021, but fell sharply in 2022 (dropping below 2019 levels) even though the number of orders was similar to 2019. This indicates that customers were placing smaller orders on average. Profit trends also differ from order trends. 2019 generated the highest profit ($818), followed by relatively close profits in 2020 and 2021. In 2022, profit decreased significantly to $708. (Note: The values in this section are based only on data from Jan–Aug for each year. This ensures comparability, since 2022 records are only available through August.)

The analysis suggests that the loyalty card program does not appear to significantly boost sales or improve customer retention. Regarding product preferences, Arabica is the most popular coffee type, while Liberica is the most profitable.
 Geographically, the US market outperforms the UK and Ireland markets. 
Below is a snapshot from the Tableau dashboard; the full interactive dashboard can be downloaded <a href="https://public.tableau.com/app/profile/xuan.dinh8619/viz/CoffeeBean_17562288415120/Dashboard3?publish=yes">here</a>.

<p align="center">
<img width="1000" height="600" alt="image" src="https://github.com/user-attachments/assets/a5342de9-a76c-4600-8069-f0d14338a5aa" />
</p>

### Customer Loyalty 

<p align="center">
<img width="300" height="160" alt="image" src="https://github.com/user-attachments/assets/98138a23-6bd3-4b58-afbc-9ad18e944624" />
</p>

The database contains 1,000 customers, but only 913 have made purchases between 2018 and 2022. The proportion of repeat customers is very low, averaging just 2.7%, despite 48.5% of customers holding a loyalty card. Surprisingly, repeat customers with a loyalty card place fewer orders and purchase smaller quantities than those without a loyalty card. Even among one-time customers, those enrolled in the loyalty program tend to have lower order quantities compared to non-loyalty customers. Hence, profit generated by loyalty program customers is much lower than that from customers not in the program.

These findings suggest that the current loyalty program may not be effectively encouraging repeat purchases or higher spending. Possible reasons could include rewards that are not compelling enough, customers being unaware of the program benefits, or the program not being properly targeted to the right customer segments. 

### Product Type 
<p align="center"> 
<img width="597" height="175" alt="image" src="https://github.com/user-attachments/assets/59d94687-ce35-4e2f-95e7-a6a5a9db0be4" />
</p>

•	Arabica is the most popular coffee type, but it yields only a 9% profit margin. Customers prefer the 0.5 kg and 2.5 kg packs, and it performs best with medium roast, while light roast pairings see weaker demand. This suggests that customers tend to favor larger sizes, are drawn to Arabica for its taste or brand familiarity, but the business earns less because pricing or perceived value may not be optimized.

•	Excelsa follows closely in sales and achieves a strong profit margin of 11%, despite higher costs. Customers mainly purchase the 0.5 kg and 1 kg packs, while the 0.2 kg pack shows the weakest performance. Light roast is the preferred pairing, whereas medium roast options are less popular. This indicates balanced performance, and with more effective promotion, Excelsa has the potential to surpass Arabica in sales.

•	Liberica has the lowest sales volume but achieves the highest profit margin at 13%, and ranks second in total profit. Customers favor the 0.5 kg pack, while the larger 2.5 kg option performs poorly. Sales lean toward light roast, whereas medium roast combinations are less appealing. This suggests that smaller or moderate pack sizes better match customer demand, and although its pricing, cost structure, and perceived value are strong, low awareness or limited customer preference may be holding back its full sales potential.

•	Robusta ranks second in total sales but delivers the weakest financial performance, with only a 6% margin despite having the lowest costs. Its strongest sales come from the 0.2 kg pack, which customers may view as a budget option, while larger packs underperform. Like the other beans, Robusta performs better with light roasts than with medium roast. This suggests that, although it is quite popular, its low pricing and budget positioning limit its profitability.

### Geography 
<p align="center"> 
<img width="300" height="100" alt="image" src="https://github.com/user-attachments/assets/5ee0656d-5f56-4df9-ba37-cc2372f4aa4c" />
</p>

The US market significantly outmatchs the UK and Ireland, with nearly 2,800 units sold, while the UK and Ireland see only a few hundred units each. As the result the US market generates the highest profit. The top-selling cities, Washington, New York, and Houston, are all in the US. Both the US and Ireland show a strong preference for Arabica beans, while the other three types also perform reasonably well. In contrast, Arabica is the least popular bean in the UK.

The strong performance in the US could be attributed to larger population sizes, higher coffee consumption per capita, and stronger brand recognition in major cities. In contrast, the UK and Ireland may have lower demand due to smaller populations, different coffee preferences

## Recommendation 
#### Customer Loyalty:
-	The analysis indicates that the current loyalty program is not effectively encouraging repeat purchases or higher spending. To address this, the business should consider rebuilding the loyalty program to create more tangible value for customers. The new program should focus on rewards that are meaningful and clearly linked to customer behavior, such as tiered benefits, exclusive discounts, or points that can be redeemed for popular products.

-	The business should take steps to boost both awareness and engagement with the loyalty program. Collaborating with the marketing team, targeted campaigns can inform customers about the benefits of the program, and make enrollment quick and easy. Using the contact information available in the database, personalized emails and text messages can remind customers of rewards, special offers, and incentives, encouraging them to make repeat purchases and engage more actively with the program.

#### Product Type:
- To increase profitability across all coffee bean types, the business should focus on strategies that enhance perceived value, optimize pack sizes, and align production with customer preferences. For example, with Arabica, which is the most popular bean, even a small increase in margin per unit could significantly boost overall profitability. Pricing and positioning can be adjusted so that customers perceive greater value in the 0.5 kg and 2.5 kg packs, which are already preferred over the smaller 0.2 kg and 1 kg packs. Slightly increasing the price of the larger packs while highlighting benefits such as better value per kilogram or exclusive flavor can raise profit without deterring purchases. Alternatively, increasing the price of the smaller packs can create the impression that the larger packs offer a better bargain, encouraging customers to buy larger one.

- The data also suggests that very large sizes, such as the 2.5 kg pack, for Excelsa, Liberica, and Robusta may be inconvenient for some customers. Introducing a slightly smaller alternative, such as 1.5 kg or 2 kg packs, could retain sales volume while improving profitability. Similarly, analyzing and aligning production with the most popular roast types, for example producing more medium roast Arabica, can reduce waste, better allocate resources, and ensure supply meets demand efficiently.

=> By combining value-based pricing, bundling strategies, marketing, and production optimization, the business can increase overall profitability while maintaining customer satisfaction and encouraging repeat purchases. 

#### Geography:
-	Method 1: Boost sales in the UK and Ireland

To increase revenue in the UK and Ireland, the business could tailor its product offering to better match local preferences. For example,adding more coffee bean type or replacing Robusta, which sells in volume but generates only a low profit margin, with a more premium or popular bean type could improve profitability. Focusing on bean types, roast type and pack sizes that appeal to UK and Ireland consumers, supported by targeted marketing campaigns and localized promotions, could help grow demand in these markets. Offering sample packs or bundles may also encourage trial and adoption.

-	Method 2: Focus resources on the US market

Given that the US is the largest and most profitable market, the business could pivot its focus to further capitalize on its strength there. Concentrating marketing, distribution, and product development efforts on top-performing US cities, such as Washington, New York, and Houston, could maximize returns. By focusing on the market with the highest sales and urban concentration, the company can drive growth and profitability more efficiently.




