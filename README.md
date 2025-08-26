# Coffee Bean Sales Performance Insights
## Background and Overview
The Coffee Bean Sales Dataset provides a detailed view of customer transactions, loyalty participation, and product preferences across US, UK, and Ireland. This project applies Excel and Tableau to explore how customer loyalty, product type, and geography influence overall sales performance. The analysis aims to uncover opportunities for improving retention and better align product offerings with customer preferences.

<img width="25" height="25" alt="image" src="https://github.com/user-attachments/assets/c7fd2787-3b30-4b70-a5d7-fb1947851fb3" />
Hypothetical Business Situation: <br />
“Brew & Bean” is a small coffee bean branch operating in the US, UK, and Ireland since 2018. Over the past four years (2018 to 2022), the brand has collected detailed data on customer purchases, product types, and loyalty program participation. In 2022, the business began showing signs of decline, prompting the management team to seek a deeper understanding of sales performance to make informed decisions regarding customer retention, product offerings, and market expansion. <br />
The shop faces several key questions:

•	Does the loyalty card program help with customer retention and boost sales?

•	Which coffee types, roasts, and sizes are the most popular and profitable, and are there opportunities to optimize inventory or promotions?

•	How do sales differ across countries and cities, and which markets show the greatest potential for growth?

The management hopes that a comprehensive analysis of historical sales data will uncover actionable insights to strengthen the business, enhance customer engagement, and guide strategic decisions.
<br />

<img width="21" height="21" alt="image" src="https://github.com/user-attachments/assets/12111bef-782c-47cd-ba3a-311b55dc679b" />
 Insights and recommendations are provided on the following key areas:

•	Customer Loyalty – Comparing loyalty card holders with non-members in terms of sales volume, profit, purchase frequency, and repeat behavior.

•	Product Type – Identifying which coffee type, roast, and size combinations drive the highest sales and profit.

•	Geography – Evaluating sales performance by country and city to highlight the strongest markets and customer preferences.

<img width="23" height="23" alt="image" src="https://github.com/user-attachments/assets/3d8baa56-2f39-452e-9edf-2efc99427de3" />
Tools:

• Excel: Data cleaning, preparation, and analysis

• Tableau: Interactive dashboard creation and visualization

• Draw.oi: The initial dashboard mockup

• Flaticon: Icon sourcing for dashboard visuals

• Paint: Icon customization and editing
<br />

Data Source: <a href="https://www.kaggle.com/datasets/saadharoon27/coffee-bean-sales-raw-dataset">here</a>.

An Interactive Tableau dashboard can be downloaded <a href="https://public.tableau.com/app/profile/xuan.dinh8619/viz/CoffeeBean_17562288415120/Dashboard3?publish=yes">here</a>.

The Excel file containing the data cleaning, preparation, and analysis work is available here.

The initial dashboard mockup can be found here.

## Data Structure Overview
The dataset consists of three tables, providing information on coffee bean Products, customer Orders, and Customer profiles.
<p align="center">
<img width="600" height="400" alt="Tables" src="https://github.com/user-attachments/assets/84f0e2ae-c2b0-4d63-b65b-6b4350e5e871" />
</p>

## Executive Summary
### Overview of Findings
The number of orders steadily increased from 159 in 2019 to 170 in 2020, reaching the highest point in 2021 (186), but then declined to 158 in 2022. However, the total quantity sold did not follow the same pattern. The quantity sold slightly declined from 2019 to 2020, even though the number of orders in 2020 was higher than in 2019. 2021 recorded the highest quantity sold, while 2022 had only 543 units sold despite a similar number of orders to 2019, indicating that customers were placing smaller orders on average.

Profit trends also differ from order trends. 2019 generated the highest profit ($818), followed by relatively close profits in 2020 ($779) and 2021 ($798). In 2022, profit decreased significantly to $708.

Analysis suggests that the loyalty card program does not appear to significantly boost sales or improve customer retention. Geographically, the US market outperforms the UK and Ireland markets.

Regarding product preferences, Arabica is the most popular coffee type, while Robusta, Liberica, and Excelsa have similar, lower popular levels.

Below is a snapshot from the Tableau dashboard; the full interactive dashboard can be downloaded <a href="https://public.tableau.com/app/profile/xuan.dinh8619/viz/CoffeeBean_17562288415120/Dashboard3?publish=yes">here</a>

<p align="center">
<img width="900" height="500" alt="Dashboard" src="https://github.com/user-attachments/assets/ace56b23-a1fa-4700-8b7d-0e88ccb17cb6" />
</p>

### Customer Loyalty 

The database contains 1,000 customers, but only 913 have made purchases. The proportion of repeat customers is very low, averaging just 2.7%, despite 48.5% of customers holding a loyalty card. Surprisingly, repeat customers with a loyalty card place fewer orders and purchase smaller quantities than those without a loyalty card. Even among one-time customers, those enrolled in the loyalty program tend to have lower order counts and quantities compared to non-loyalty customers. Additionally, profit generated by loyalty program customers is lower than that from customers not in the program.

These findings suggest that the current loyalty program may not be effectively encouraging repeat purchases or higher spending. Possible reasons could include rewards that are not compelling enough, customers being unaware of the program benefits, or the program not being properly targeted to the right customer segments. Overall, the data indicates that simply offering a loyalty card is insufficient to drive stronger engagement or retention.

### Product Type 
•	Arabica is the most popular coffee type, selling 940 units, but it produces only a 9% profit margin. Customers prefer the 0.5 kg and 2.5 kg packs, which often reduce profitability because of bulk pricing. It performs strongest with medium roast, while light roast pairings see weaker demand. This suggest that customers like Arabica for taste or brand familiarity, but the business earns less because of price of packaging strategy.

•	Excelsa follows closely in sales and achieves stronger profitability at 11%, even though its costs are higher. Customers buy mainly the 0.5 kg and 1 kg packs, with the 0.2 kg pack showing the weakest performance. Light roast is the preferred pairing, while medium roast options lag behind. This indicates a balanced performance, with the potential to overtake Arabica if promoted more effectively.

•	Liberica has the lowest sales volume but achieves the highest profit margin at 13%. Customers favor the 0.5 kg pack, while the larger 2.5 kg option performs poorly. Sales lean toward light roast, while medium roast combinations are less appealing. This suggests that low awareness or limited customer preference is holding back its sales.

•	Robusta ranks second in total sales but delivers the weakest financial performance, with only a 6% margin despite having the lowest costs. Its strongest sales come from the 0.2 kg pack, which customers view as a budget option, while larger packs underperform. Like the other beans, Robusta performs better with light roasts than with medium roast. This suggests that, although it is popular, its low pricing and budget positioning limit its profitability.

### Geography 
<p align="center"> 
<img width="250" height="90" alt="image" src="https://github.com/user-attachments/assets/06137249-61c4-4de8-a8fa-fa2c40570b4f" />
</p>

The US market significantly outperforms the UK and Ireland, with nearly 2,800 units sold, while the UK and Ireland see only a few hundred units each. As the result the US market generates the highest profit. The top-selling cities, Washington, New York, and Houston, are all in the US. 

The strong performance in the US could be attributed to larger population sizes, higher coffee consumption per capita, and stronger brand recognition in major cities. In contrast, the UK and Ireland may have lower demand due to smaller populations, different coffee preferences

## Recommendation 
#### Customer Loyalty:
-	The analysis indicates that the current loyalty program is not effectively encouraging repeat purchases or higher spending. To address this, the business should consider rebuilding the loyalty program to create more tangible value for customers. The new program should focus on rewards that are meaningful and clearly linked to customer behavior, such as tiered benefits, exclusive discounts, or points that can be redeemed for popular products.

-	The business should take steps to boost both awareness and engagement with the loyalty program. Collaborating with the marketing team, targeted campaigns can inform customers about the benefits of the program, and make enrollment quick and easy. Using the contact information available in the database, personalized emails and text messages can remind customers of rewards, special offers, and incentives, encouraging them to make repeat purchases and engage more actively with the program.

#### Product Type:
- To increase profitability across all coffee bean types, the business should focus on strategies that enhance perceived value, optimize pack sizes, and align production with customer preferences. For example, with Arabica, which is the most popular bean, even a small increase in margin per unit could significantly boost overall profitability. Pricing and positioning can be adjusted so that customers perceive greater value in the 0.5 kg and 2.5 kg packs, which are already preferred over the smaller 0.2 kg and 1 kg packs. Slightly increasing the price of the larger packs while highlighting benefits such as better value per kilogram or exclusive flavor can raise profit without deterring purchases. Alternatively, increasing the price of the smaller packs can create the impression that the larger packs offer a better bargain, encouraging customers to buy larger one.
- Similarly, other beans such as Excelsa, Liberica, and Robusta could benefit from tailoring pack sizes to match customer demand and convenience. Targeted marketing can emphasize the unique qualities of each bean and reinforce their value, while production should focus on the most popular roast types to reduce waste and better allocate resources.

=> By combining value-based pricing, bundling strategies, marketing, and production optimization, the business can increase overall profitability while maintaining customer satisfaction and encouraging repeat purchases. 

#### Geography:
-	Option 1: Boost sales in the UK and Ireland
To increase revenue in the UK and Ireland, the business could tailor its product offering to better match local preferences. For example, replacing Robusta, which sells in volume but generates only a low profit margin, with a more premium or popular bean type could improve profitability. Focusing on bean types and pack sizes that appeal to UK and Ireland consumers, supported by targeted marketing campaigns and localized promotions, could help grow demand in these markets. Expanding distribution in key urban areas and offering sample packs or bundles may also encourage trial and adoption.

-	Option 2: Focus resources on the US market
Given that the US is the largest and most profitable market, the business could pivot its focus to further capitalize on its strength there. Concentrating marketing, distribution, and product development efforts on top-performing US cities, such as Washington, New York, and Houston, could maximize returns. Strategies could include expanding premium offerings, optimizing pack sizes to improve margins, and strengthening brand presence in high-demand regions. By focusing on the market with the highest sales and urban concentration, the company can drive growth and profitability more efficiently.




