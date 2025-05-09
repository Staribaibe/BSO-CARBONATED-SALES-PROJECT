
# TECHNICAL REPORT ON CARBONATED DRINKS SALES PERFORMANCE IN THE UNITED STATES BETWEEN 2022 THROUGH 2023

## Introduction

Making data-driven decisions in the highly competitive beverage industry of today requires an awareness of market dynamics, profitability, and sales success. The sales and operational data from several beverage brands and retailers in the USA, are thoroughly analysed in this technical research, which offers insightful information on regional market trends, retailer performance, product profitability, and sales distribution.

This research analyses key performance indicators (KPIs) such as total sales, operational profit, units sold, and regional contributions using data from West Soda, BevCo, FizzyCo, and large retailers like Target, Amazon, and Walmart. This research highlights cost inefficiencies and profitability issues while identifying high-performing markets, underperforming regions, and possible expansion prospects.

In order to provide actionable insights to improve product distribution, hone pricing strategies, and fortify regional market penetration, the research also examines seasonal sales trends, price effectiveness, and retailer-specific sales success. Stakeholders can improve profitability, operational effectiveness, and long-term market growth by using this data to inform their decisions.

## Objective of Project

The objective of this project is to evaluate sales performance, profitability, and market trends across different beverage brands, regions, and retailers. By examining key metrics such as total sales, operating profit, units sold, and regional distribution, the analysis aims to identify high-performing products, assess regional market trends, and evaluate retailer effectiveness. Additionally, it seeks to optimize pricing strategies, detect seasonal sales fluctuations, and improve operational efficiency by highlighting cost inefficiencies and resource allocation opportunities. Ultimately, the goal is to provide actionable insights that support strategic decision-making, enhance profitability, and drive business growth.

## Problem Being Addressed

This project addresses several critical business challenges in the beverage industry in USA by providing insights into sales inefficiencies, pricing issues, regional market disparities, and retailer performance gaps. It helps identify high-performing and underperforming products, allowing businesses to optimize their product offerings based on demand and profitability. The dataset also reveals regional market trends, highlighting areas of strong and weak sales penetration to guide investment and marketing strategies. Additionally, it evaluates the effectiveness of different retailers, comparing direct brand sales with major retail partners like Walmart, Amazon, and Target to optimize sales channels. By analyzing pricing and profitability, the dataset helps refine pricing strategies to maximize revenue while maintaining healthy margins. Seasonal sales trends are also assessed to improve demand forecasting and inventory management. Furthermore, the dataset highlights operational inefficiencies and cost-heavy regions, allowing businesses to enhance logistics and supply chain strategies. Ultimately, this analysis supports data-driven decision-making to improve profitability, streamline operations, and expand market reach.


## Key Datasets and Methodologies


The dataset consists of multiple key data categories, including sales performance data, profitability and cost data, regional and geographic data, retailer performance data, product category data, and time-series data. Sales performance data captures total sales, units sold, and price per unit, providing insights into overall revenue generation and demand. Profitability and cost data include operating profit and margin, helping to assess product and regional profitability. Regional and geographic data enable market segmentation analysis, while retailer performance data compare direct brand sales with major retailers. Product category data highlight the best-selling beverages, and time-series data track seasonal trends and growth patterns.
To analyze these datasets, i used percentage contributions, sales and profitability analysis comparing revenue and profit margins to identify high-performing products and retailers. Regional and retailer performance analysis to examine sales distribution to optimize market expansion. Time-series and trend analysis to track seasonal sales fluctuations, while price sensitivity analysis evaluates how pricing affects demand and profitability. Competitive benchmarking was used to compare brand and retailer performance, supporting strategic decision-making for resource allocation, marketing, and distribution. 
Together, these methodologies provide actionable insights to enhance sales, profitability, and operational efficiency. All these were performed using pivot tables in excel.

## Story of Data

### Our Data Source

The project's dataset came from Kaggle, a popular site for data science and machine learning datasets. Kaggle offers a huge selection of publicly accessible datasets that have been given by scholars, organisations, and data professionals, making it an invaluable tool for performing data-driven analysis. This particular dataset includes comprehensive information on market performance, sales, and profitability for a range of beverage brands, retailers, and geographical areas. It is set up to make it easier to analyse pricing plans, retail performance, operational efficiencies, and sales trends in-depth. Statistical and visual analysis methods were used to pre-process and analyse the data in order to derive valuable insights that can aid in business decision-making.

### Data Collection Process

The data collection process for this dataset likely involved gathering sales and operational data from various retail and distribution channels, including point-of-sale (POS) systems, enterprise resource planning (ERP) systems, and financial reporting tools. Retailers such as Walmart, Amazon, and Target, along with direct beverage brands like West Soda, BevCo, and FizzyCo, contributed transactional records, including total sales, units sold, operating profit, and pricing details.
Additionally, regional sales data was collected to assess market trends across different geographic locations. The dataset may have undergone data cleaning, aggregation, and validation to ensure accuracy before being made publicly available on Kaggle. The final dataset was structured in a tabular format, allowing for in-depth analysis of sales performance, profitability trends, retailer effectiveness, and seasonal demand variations.

### The Data Structure

The data structure of this dataset is organized in a tabular format, where each row represents a sales transaction or an aggregated sales record from different beverage brands, retailers, and regions. The dataset consists of categorical, numerical, and date/time fields, enabling comprehensive analysis.
Categorical fields include retailer names, beverage brands, regions, states, and cities, which help segment the data based on market distribution. Numerical fields such as total sales, units sold, operating profit, and price per unit provide key performance metrics for evaluating revenue and profitability. The dataset also contains a date/time field (Invoice Date), which allows for time-series analysis to track seasonal trends and monthly sales fluctuations.

### Key Data Variables


The dataset contains several key variables that provide insights into sales performance, profitability, and market trends. These variables fall into three main categories: categorical, numerical, and date/time fields.
Categorical variables classify the data into distinct groups, helping with segmentation and comparative analysis. The Retailer variable identifies the store or platform selling the beverages, such as Walmart, Amazon, Target, West Soda, BevCo, and FizzyCo. The Beverage Brand variable specifies the type of beverage sold, including Coca-Cola, Diet Coke, Sprite, Dasani Water, Powerade, and Fanta. Region, State, and City variables provide geographic information that helps analyze regional sales trends and market performance.
Numerical variables measure key performance indicators related to revenue, sales volume, and profitability. Total Sales represents the total revenue generated from beverage sales, while Units Sold shows the total quantity of beverage units sold. Price per Unit indicates the selling price of each beverage, which influences demand and revenue. Operating Profit measures the profit earned after deducting operational costs, while Operating Margin calculates the percentage of revenue converted into profit, providing insights into overall efficiency.
The dataset also includes a date/time variable, Invoice Date, which records when each sales transaction occurred. This allows for trend analysis and forecasting by identifying seasonal fluctuations and changes in demand over time.
These key variables are essential for analyzing market trends, optimizing pricing strategies, evaluating retailer performance, and improving profitability. By leveraging this data, businesses can make informed decisions on product distribution, market expansion, and operational efficiency.

## Data Splitting and Preprocessing

### Data Cleaning and Handling of Missing Values

The dataset underwent a data cleaning process to ensure accuracy and consistency. This involved checking for duplicate entries, inconsistent formatting, and invalid data points. Missing values were handled by removing incomplete records. Additionally, categorical variables were standardized to maintain uniformity, and numerical values were checked for anomalies.

### Industry Context

The dataset is relevant to the beverage industry, where companies need to understand sales trends, profitability, and market performance across different retailers and regions. The industry is highly competitive, with businesses striving to optimize pricing strategies, distribution networks, and product demand forecasting to gain a competitive edge. Insights derived from this data help businesses improve revenue streams, operational efficiency, and market positioning.

### Stakeholders

Key stakeholders who benefit from this dataset include business executives, sales managers, marketing teams, supply chain analysts, and retail partners. Executives use the insights for strategic decision-making, while sales and marketing teams leverage the data to identify growth opportunities and optimize campaigns. Retail partners and supply chain analysts utilize the data for inventory management and distribution efficiency.

### Value to the Industry

This dataset provides significant value to the beverage industry by offering data-driven insights into sales performance, profitability, and market expansion opportunities. Companies can use it to optimize pricing, improve supply chain efficiency, forecast demand, and strengthen retailer relationships. By leveraging data analytics, businesses can enhance decision-making processes, reduce operational costs, and maximize revenue growth in a highly competitive market.

## Pre- Analysis
   
The dataset reveals significant variations in sales, profitability, and regional performance, with the West region and direct brand distributors (West Soda, BevCo, and FizzyCo) leading in revenue. Despite high sales, not all products and regions contribute equally to profitability, with Coca-Cola and Dasani Water performing best, while Fanta has lower margins. Traditional retailers like Walmart underperform compared to Amazon and Target, indicating possible distribution or pricing issues.
Sales trends show strong growth in 2023, with December being the highest-performing month, suggesting seasonal demand fluctuations. Pricing strategies influence sales differently across brands, with Coca-Cola maintaining high sales despite higher prices, while Fanta and Powerade may need adjustments. The Midwest remains an underperforming region, but it could present growth opportunities with optimized pricing and marketing strategies.

## In Analysis Observations
   
The Key performance indicators for this project for year 2022 and 2023 showed that total revenue was $12,016,665, total units sold 24,788,610 and total operating profit $4,722,497.
It has been noticed that the sales in 2023 were more that the sales in 2022.
The region with the highest number of sales was the west, followed by the northest, while the midwest had the lowest sales.
The company saw highest sale in New York while Nebraska had lowest sale 

In terms of retailers, west soda had the highest sale and Walmart had the lowest.
Coca cola was its best performing beverage brand in terms of sales while Fanta had the lowest sale 

### Unconfirmed Insights

Investigating marketing campaigns, pricing strategies, and customer acquisitions in early 2023 could reveal the reason for the increased sale.
Investigate what’s working in the West and apply similar strategies to underperforming regions.
Since New York, California, Florida, and Texas contribute the most, consider expanding marketing, inventory, and promotions in these states to maximize revenue potential.
States like South Carolina, Louisiana, and Washington show promising sales. Investing in these areas could drive additional growth.
Investigate whether West Soda has better pricing, distribution, or brand loyalty. If possible, apply their successful strategies to other brands.

## Post-Analysis and Insights

### Key Findings

#### Sales Performance & Regional Distribution
   
•	The West region is the highest revenue contributor, generating $3.64 million (~30% of total sales), while the Midwest has the lowest sales ($1.67 million, ~13.9%).

•	The Northeast and South are strong markets, contributing $2.5 million and $2.06 million, respectively, while the Southeast falls slightly behind at $2.13 million.

•	The Midwest underperforms in both sales and profitability, indicating lower demand or distribution inefficiencies.

#### Retailer Performance Insights

•	West Soda leads in total sales ($3.24 million) and units sold (6.25 million), followed by BevCo ($2.79 million, 5.85 million units) and FizzyCo ($2.42 million, 5.46 million units).

•	Among major retailers, Target ($1.35 million) and Amazon ($1.28 million) outperform Walmart ($920K), which has the lowest sales.

•	Walmart also has the lowest units sold (1.85 million), indicating weaker product visibility or consumer demand in its stores.

#### Brand Performance & Profitability

•	Coca-Cola is the best-selling beverage brand ($2.77 million in total sales), followed by Dasani Water ($2.39 million) and Diet Coke ($2.05 million).

•	Coca-Cola is also the most profitable brand, contributing $1.16 million in operating profit, followed by Dasani ($968K) and Diet Coke ($743K).

•	Fanta has the lowest profitability ($559K), despite having $1.43 million in sales, indicating lower pricing power or higher costs.

•	Powerade and Sprite have moderate sales but lower profit margins, suggesting potential cost inefficiencies or pricing optimization opportunities.

#### Pricing and Demand Relationship
   
•	Higher-priced products, such as Coca-Cola and Diet Coke, maintain strong demand, suggesting brand loyalty and less price sensitivity.

•	Lower-priced brands like Fanta and Powerade show lower profitability, indicating the need for price adjustments or cost optimizations.

#### Seasonal Sales & Growth Trends
   
•	Sales in 2022 were relatively low, with a major increase in 2023.

•	December 2023 recorded the highest sales ($1.03 million), while June and December 2022 had the lowest sales.

•	YoY (Year-over-Year) growth shows a significant jump from 2022 to 2023, indicating expanded market penetration or improved sales strategies.

#### Operating Profit by Region
    
•	The West region leads in operating profit ($1.3 million), followed by the Northeast ($973K) and the South ($922K).

•	The Southeast and Midwest have the lowest profit margins, suggesting higher operational costs or lower sales efficiency.

#### Profitability by Retailer
    
•	West Soda, BevCo, and FizzyCo generate higher operating profits than traditional retailers.

•	Despite its brand reputation, Walmart has the lowest contribution to total profit, aligning with its lower sales performance.

### Counterintuitive Findings & Unexpected Trends

1.	Walmart’s Underperformance: Despite being a major retailer, Walmart had the lowest sales and units sold, showing that direct brand distribution (West Soda, BevCo, FizzyCo) is significantly more effective than large-scale retailers in driving beverage sales.

2.	Dasani Water’s High Profitability: It was expected that soft drinks like Coca-Cola would dominate profitability, but Dasani Water had the second-highest profit, indicating strong demand for bottled water and potential for market expansion in the category.

3.	Fanta’s Low Profitability Despite Decent Sales: Fanta had reasonable sales volume but lower-than-expected profits, showing inefficiencies in pricing or production costs.

4.	Southeast’s Low Margins: Although the Southeast had a relatively strong sales performance, its profitability was lower than anticipated, meaning there may be operational inefficiencies or cost-heavy logistics in the region.

5.	December 2023’s Extreme Growth: While some seasonality was expected, the significant jump in December 2023’s sales compared to December 2022 suggests that external factors, such as promotional campaigns or shifts in consumer behavior, played a large role.

## Dashboard and Charts

![image](https://github.com/user-attachments/assets/f628c6ed-34d0-4941-9b2f-37b685ec3087)
 

## Recommendations and Observations

 ### Observations  
   
•  The West region leads in sales and profitability ($3.64M in sales, $1.3M in profit), while the Midwest underperforms ($1.67M sales, $685K profit). The Southeast has good sales volume but low profit margins, indicating potential cost inefficiencies.

•  West Soda, BevCo, and FizzyCo outperform major retailers, contributing over 60% of sales. Walmart underperforms ($920K in sales, 1.85M units sold), while Target and Amazon show stronger retail sales.

•  Coca-Cola and Dasani Water are the most profitable brands ($1.16M and $968K in profit, respectively), while Fanta struggles with profitability despite decent sales.

•  Sales peaked in December 2023 ($1.03M), while mid-year months like June 2022 had the lowest sales (~$108K).

•  Dasani Water is the second-best-performing brand in both sales ($2.39M) and profit ($968K), showing strong demand for bottled water.

•  The Southeast has relatively high sales but lower-than-expected profit margins, suggesting operational inefficiencies.

•  Amazon ($1.28M) performs better than Walmart ($920K) in total sales, suggesting a stronger online presence is needed.

## Recommendations

•	Prioritize investments in the West and Northeast to sustain and grow market dominance.

•	Expand targeted marketing campaigns in the Midwest and Southeast, improving pricing strategies or reducing costs to increase profitability.

•	Optimize distribution in the Southeast to reduce operational costs and improve margins.

•	Strengthen direct brand distribution (West Soda, BevCo, FizzyCo), which yields higher sales and profit.

•	Expand partnerships with Target and Amazon, leveraging their stronger retail performance.

•	Assess and improve Walmart’s retail presence through better shelf placement, targeted discounts, or exclusive product bundles.

•	Maintain premium pricing for Coca-Cola and Dasani Water, as they retain strong demand even at higher prices.

•	Re-evaluate Fanta’s pricing strategy—consider increasing its price slightly or reducing operational costs to improve margins.

•	Introduce tiered pricing or bundling strategies (e.g., Fanta with Coca-Cola) to drive higher revenue.

•	Increase production and marketing efforts leading up to high-demand months (e.g., Black Friday, holiday season).

•	Offer discounts and promotions in low-sales months (e.g., June-July) to boost sales during slow periods.

•	Use predictive modeling to better forecast inventory needs and prevent stockouts during peak sales periods.

•	Expand distribution for Dasani Water into more retailers and online platforms to capitalize on increasing demand.

•	Introduce new product variations, such as flavored water or vitamin-enriched options, to attract health-conscious consumers.

•	Consider bundling water with soft drinks to increase cross-category sales.

•	Optimize supply chain operations in the Southeast, reviewing logistics and transportation costs to improve margins.

•	Evaluate retailer partnerships and operational expenses in the region to find cost-saving opportunities.

•	Adjust pricing in cost-heavy regions to ensure profitability while maintaining competitive sales volume.

•	Expand e-commerce marketing on Amazon and Walmart.com, using targeted ads and promotions.

•	Offer online-exclusive bundles to encourage bulk purchasing.

•	Enhance direct-to-consumer (DTC) sales strategies through brand-owned websites and social media-driven sales campaigns.

•	Review production and supply chain costs for Fanta to find inefficiencies.

•	Test alternative pricing strategies to determine optimal price points for better profitability.

•	Promote Fanta through combo deals or cross-brand promotions to increase its sales volume and improve margins.



##  Final Summary of Key Business Improvements

1.	Prioritize expansion in high-growth regions (West, Northeast) and optimize cost efficiency in the Midwest and Southeast.
3.	Strengthen direct brand distribution while improving retail partnerships, particularly with Target and Amazon.
4.	Adjust pricing strategies to boost profits, especially for Fanta and Powerade, which have lower margins.
5.	Capitalize on seasonal demand trends by launching strategic promotions during low-sales months and increasing stock during peak periods.
6.	Leverage the growing bottled water market by expanding Dasani’s distribution and introducing new product variations.
7.	Reduce operational inefficiencies in the Southeast and other high-cost regions to improve profit margins.
8.	Enhance e-commerce strategies through better online promotions and direct-to-consumer sales models.
9.	Reassess cost structures for lower-margin products, optimizing production, pricing, and bundling strategies.



## Conclusion


This analysis of beverage sales, profitability, and market trends has provided critical insights into sales performance, retailer efficiency, regional distribution, and pricing strategies. The key findings highlight that West Soda, BevCo, and FizzyCo outperform traditional retailers, Coca-Cola and Dasani Water lead in profitability, and seasonal trends significantly impact sales volume. Additionally, Walmart underperforms compared to Amazon and Target, and certain brands like Fanta show strong sales but weaker profitability due to potential cost inefficiencies.

### Key Learnings
The analysis confirms that direct brand distribution is more effective than relying solely on major retailers and that pricing strategies play a crucial role in profitability. Seasonal variations significantly influence demand, with December 2023 being a peak sales month, while mid-year periods like June 2022 saw the lowest sales. Regional market differences are evident, with the West leading in both sales and profit, while the Midwest and Southeast require optimization. Bottled water (Dasani) is an increasingly profitable category, indicating growing consumer demand for healthier beverage options.

### Limitations

Despite its valuable insights, this analysis has some limitations. The dataset does not include consumer demographics or purchasing behaviors, making it difficult to determine why some regions or retailers underperform. External factors such as competitor pricing, promotional campaigns, and economic conditions are not accounted for, which may have influenced sales trends. Additionally, the dataset primarily focuses on past sales performance, meaning it does not provide predictive insights into emerging market trends, new consumer preferences, or product innovation opportunities.

## Future Research Directions

To expand on these findings, future research should incorporate consumer behavior analysis, competitive benchmarking, and demand forecasting models. Including customer segmentation data (age, income, buying habits) would help refine marketing and pricing strategies. A deeper analysis of retailer-specific sales drivers (e.g., promotional effectiveness, shelf placement, online vs. in-store sales) could enhance retailer partnerships. Finally, machine learning models for sales prediction and price optimization could provide more dynamic decision-making capabilities for the business, helping it stay ahead of industry trends.
By addressing these areas, businesses can move from reactive insights to proactive strategies, ensuring continued revenue growth, cost efficiency, and market leadership in the beverage industry. 

