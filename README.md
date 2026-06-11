# Coffee Bean Sales: Performance Insights
## Background and Overview
The Coffee Bean Sales dataset provides a detailed view of customer transactions, loyalty participation, and product preferences across US, UK, and Ireland. This project applies Excel and Tableau to explore how customer loyalty, product type, and geography influence overall sales performance. The analysis aims to uncover opportunities for improving retention and better align product offerings with customer preferences.

<img width="25" height="25" alt="image" src="https://github.com/user-attachments/assets/c7fd2787-3b30-4b70-a5d7-fb1947851fb3" />
Business Situation: 
“Brew & Bean” is a coffee bean brand operating in the US, UK, and Ireland. Over a four-year period (2018 to 2022), the brand collected detailed data on customer purchases, product profiles, and loyalty program participation. In 2022, the business began showing signs of a performance decline, prompting the management team to seek a deeper understanding of sales trends to make informed decisions regarding customer retention, product optimization, and market expansion.

####  
The shop faces several key questions:

•	Does the loyalty card program effectively drive customer retention and boost top-line sales?

•	Which coffee types, roasts, and pack sizes are the most popular and profitable, and where are the opportunities to optimize inventory or promotional spend?

•	How do sales variance patterns differ across countries and cities, and which regional markets show the greatest potential for scalable growth?

The management hopes that a comprehensive analysis of historical sales data will uncover actionable insights to strengthen the business, enhance customer engagement, and guide strategic decisions.

<img width="25" height="25" alt="analysis" src="https://github.com/user-attachments/assets/e696f319-6456-4ac1-8a34-e643cbb72db6" />
 Insights and recommendations are provided on the following key areas:

 ####  
•	Customer Loyalty: Comparing loyalty card holders with non-members in terms of sales volume, profitability, purchase frequency, and repeat behavior.

•	Product Type: Identifying which coffee type, roast, and size combinations drive the highest sales volume and margin performance.

•	Geography: Evaluating sales performance by country and city to highlight regional market strengths and localized customer preferences

<img width="23" height="23" alt="image" src="https://github.com/user-attachments/assets/3d8baa56-2f39-452e-9edf-2efc99427de3" />
Tools:

####  
• Excel (Power Pivot): Data cleaning, preparation, and analysis

• Tableau: Interactive dashboard creation and visualization

• Draw.io: The initial dashboard mockup

•	Flaticon & Paint: Custom icon sourcing, asset design, and dashboard visual editing.

Data Source: <a href="https://www.kaggle.com/datasets/saadharoon27/coffee-bean-sales-raw-dataset">Coffee Bean Sales Raw Dataset</a>.

An Interactive Tableau dashboard can be downloaded <a href="https://public.tableau.com/app/profile/xuan.dinh8619/viz/CoffeeBean_17562288415120/Dashboard3?publish=yes">here</a>.

The Excel file containing the data cleaning, preparation, and analysis work is available <a href="https://github.com/xuandinh22/Coffee-Bean-Sales-Performance-Insights/blob/main/Coffee%20Bean%20Project.xlsm">here</a>.

The initial dashboard mockup can be found  <a href="https://github.com/xuandinh22/Coffee-Bean-Sales-Performance-Insights/blob/main/Dashboard%20Mockup.pdf">here</a>.

## Data Structure Overview
The dataset consists of three tables, providing information on coffee bean Products, customer Orders, and Customer profiles.
<p align="center">
<img width="600" height="300" alt="Tables" src="https://github.com/user-attachments/assets/84f0e2ae-c2b0-4d63-b65b-6b4350e5e871" />
</p>

## Executive Summary
### Overview of Findings
The total number of orders rose steadily from 2019 to 2020, peaked in 2021, and subsequently declined in 2022. However, the total quantity sold followed a slightly different pattern. Although more orders were placed in 2020 than in 2019, the net quantity sold slightly decreased. Sales volume reached its historical baseline peak in 2021 but fell sharply in 2022 (dropping below 2019 levels), even though total order counts remained similar to 2019. This indicates that customers were placing smaller orders on average. 
Profit trends also diverged from volume trends. 2019 generated the highest overall profit ($818), followed by relatively flat performance across 2020 and 2021. In 2022, profit decreased significantly to $708. (Note: The values in this section are normalized using data from January to August for each fiscal year to ensure structural comparability, as 2022 records are only available through August).

The analysis suggests that the current loyalty card program does not appear to significantly boost sales volume or improve customer retention metrics. Regarding product preferences, Arabica remains the most popular coffee type by volume, while Liberica proves to be the most profitable SKU line. Geographically, the US market significantly outperforms the UK and Ireland. 
Below is a snapshot from the Tableau dashboard; the full interactive dashboard can be downloaded <a href="https://public.tableau.com/app/profile/xuan.dinh8619/viz/CoffeeBean_17562288415120/Dashboard3?publish=yes">here</a>.

<p align="center">
<img width="2000" height="1200" alt="image" src="https://github.com/user-attachments/assets/2037f746-4643-44c1-95d4-b05d1e4bf4a7" />
</p>

### Customer Loyalty 

<p align="center">
<img width="310" height="170" alt="image" src="https://github.com/user-attachments/assets/b5647583-cde3-4ceb-ba40-4ecbf63ee63e" />
</p>

The database tracks 1,000 customers, but only 913 have made purchases between 2018 and 2022. The proportion of repeat customers is remarkably low, averaging just 2.7%, despite a high loyalty program adoption rate of 48.5%. Surprisingly, repeat customers with a loyalty card place fewer orders and purchase smaller on average than non-members.
Even among one-time buyers, those within the loyalty program exhibit lower order quantities compared to standard customers. Consequently, total profit generated by loyalty program participants is significantly lower than that from non-enrolled consumers. These findings indicate that the current loyalty program fails to effectively encourage repeat purchases or higher basket spend, likely due to uncompelling rewards, low programmatic awareness, or poor customer segmentation targeting.

### Product Type 
<p align="center"> 
<img width="597" height="175" alt="image" src="https://github.com/user-attachments/assets/59d94687-ce35-4e2f-95e7-a6a5a9db0be4" />
</p>

•	Arabica: This is the most popular coffee type by volume but yields a tight 9% profit margin. Customers favor the 0.5 kg and 2.5 kg pack sizes combined with a medium roast, while light roast configurations see weak demand. This indicates that while brand familiarity drives high volume, unit profitability remains unoptimized due to current pricing structures.

•	Excelsa: This line follows closely in sales and achieves a strong profit margin of 11% despite higher landing costs. Consumption is concentrated in 0.5 kg and 1 kg packs, whereas the 0.2 kg size underperforms. Light roast is the preferred pairing. With targeted promotional backing, Excelsa possesses the capacity to surpass Arabica in gross sales.

•	Liberica: This product line generates the lowest sales volume but captures the highest individual profit margin at 13%, ranking second in total profit contribution. Demand is concentrated in the 0.5 kg pack, while the 2.5 kg option underperforms. Sales lean heavily toward light roasts. This suggests smaller pack sizes align better with customer demand, but low brand awareness restricts its total growth runway.

•	Robusta: This bean ranks second in total sales volume but delivers the weakest financial performance, yielding a minimal 6% margin despite maintaining the lowest underlying cost structure. Demand is driven almost entirely by the 0.2 kg pack, suggesting consumers view this SKU primarily as a budget option. Its low pricing framework severely limits its capacity for margin contribution.


### Geography 
<p align="center"> 
<img width="350" height="150" alt="image" src="https://github.com/user-attachments/assets/58db8633-bd6b-4465-9949-83da59ecc98c" />

</p>

The US market significantly outmatches the UK and Ireland, representing nearly 2,800 units sold compared to a few hundred units in European regions. Consequently, the US acts as the primary driver of organizational profit, led by Washington, New York, and Houston. Both the US and Ireland demonstrate strong customer alignment with Arabica beans, whereas Arabica represents the lowest-performing bean category within the UK market. The strong performance in the US is attributed to larger localized populations, higher per-capita coffee consumption, and mature brand recognition across major metropolitan hubs.

## Recommendation 
1.	Customer Loyalty Program Restructuring:
• Value Proposition Realignment: To address the retention gap, management should rebuild the loyalty infrastructure to offer tangible, behavior-driven value. The updated framework should transition to tiered benefits, instant-redeemable points, or exclusive discounts tied directly to high-margin products to properly incentivize repeat purchase behaviors.

• Targeted Engagement & Lifecycle Marketing: The business must actively drive programmatic awareness. Integrating with the marketing team, targeted campaigns should utilize clean customer contact data to deploy automated follow-up cadences, personalized SMS/email reminders, and lifecycle milestone rewards to systematically convert one-time buyers into active repeat accounts.

2.	Product Portfolio & Pricing Optimization
• Margin Adjustment for High-Volume SKUs: Because Arabica represents the brand’s highest volume driver, a minor optimization in unit pricing could disproportionately boost net profitability. Management should adjust pricing structures to capture premium value on the preferred 0.5 kg and 2.5 kg sizes, or increase the price of 0.2 kg options to make larger, high-margin packs look like a superior value proposition.

• Inventory Management and Size Tailoring: Given that 2.5 kg sizes underperform across Excelsa, Liberica, and Robusta, management should phase out these slow-moving SKUs. Introducing a mid-tier alternative (e.g., 1.5 kg or 2 kg packs) would better match customer preferences while reducing warehousing overhead. Furthermore, aligning production schedules strictly to preferred roast profiles (such as medium-roast Arabica and light-roast Excelsa) will optimize supply chain efficiency and minimize manufacturing waste.

3.	Geographic Resource Allocation:
• Scenario A: European Market Optimization (UK & Ireland Focus)
To stimulate revenue traction across the UK and Ireland, product assortments must be localized. Management should replace low-margin Robusta offerings with premium bean types tailored to specific regional preferences. Supporting these markets with localized sampler bundles and targeted regional marketing will help scale adoption and improve cross-border margins

• Scenario B: Strategic Asset Reallocation (US Core Expansion) 
Given that the US generates the highest return on investment, the organization should execute a dual expansion-and-protection strategy. This entails aggressively redirecting marketing, distribution, and inventory capital away from underperforming, under-$1K markets (such as Saudi Arabia, Bahrain, and the Czech Republic) and consolidating resources into proven, high-velocity US metropolitan growth vectors to maximize scalable returns.



