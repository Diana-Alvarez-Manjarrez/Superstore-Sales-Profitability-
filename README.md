# Superstore Sales & Profitability 
## Problem Statement
The objective of this project is to evaluate the sales and profitability performance of the retail superstore across different regions, states and product categories. While total revenue may appear strong at the surface level, looking at individual states and what can improve can help improve profitability and sustainability.

## Business Problem
Which regions, states, and product categories are driving profit and which are causing losses? Where should the company focus on growth?

## Why is it important?
Understanding profit performance is essential for:
•	Identifying underperforming markets<br>
•	Reducing financial losses<br>
•	Optimizing pricing and discount strategies<br>
•	Improving inventory and product mix decisions<br>
•	Supporting long-term business growth<br>
Without this a company can risk promoting loss generating products.

## Data Description
The Superstore dataset  contains historical retail transaction data:
•	Order date and ship date<br>
•	Sales revenue and profit<br>
•	Discounts <br>
•	Product category and subcategory<br>
•	Customer segments<br>
•	Geographical location (Region, State, City)<br>

## Data preparation and tools used
Tools used:<br>
•	Tableau (for dashboard visualizations)<br>
•	Excel (Data formatting and validation)<br>

## Data preparation:
•	Standardized date fields for trend analysis <br>
•	Created calculated fields for:<br>
&nbsp;&nbsp;&nbsp;&nbsp;o	Profit margin<br>
&nbsp;&nbsp;&nbsp;&nbsp;o	YoY sales growth<br>
&nbsp;&nbsp;&nbsp;&nbsp;o	Total sales and total profit<br>
•	Grouped states into profit vs loss categories<br>
•	Built dynamic filters for<br>
&nbsp;&nbsp;&nbsp;&nbsp;o	Region<br>
&nbsp;&nbsp;&nbsp;&nbsp;o	Category<br>
&nbsp;&nbsp;&nbsp;&nbsp;o	Time period<br>

## Dashboards and Visuals created
This dashboards shows visualizations for:<br>
•	Sales and profit trends over time<br>
•	United States Map with Profit gain and loss distribution by state<br>
&nbsp;&nbsp;&nbsp;&nbsp;o	Red states show profit loss (Top 3 profit loss states in dark red)<br>
&nbsp;&nbsp;&nbsp;&nbsp;o	Green states show profit (Top 3 states in dark green)<br>
•	Percentage makeup table for each category (Technology, Office Supplies, and Furniture<br>
•	Category and sub category profitability table<br>
• City Table showing either profit gains or loss<br>
<img width="1655" height="845" alt="Superstore dash" src="https://github.com/user-attachments/assets/b9afbb83-b712-4852-8c61-4e84130d0c8e" />

The second visualization provides a detailed drill-down of Texas, where the data updates to reflect state-level performance. Over the past five years, Texas has recorded a total profit loss of $25,729, driven primarily by the Office Supplies category, followed by Furniture. The accompanying city-level breakdown highlights where these losses originate, with Houston ranking as the top loss-generating city.
<img width="1649" height="825" alt="Texas" src="https://github.com/user-attachments/assets/08b0fd0c-75fb-4355-8b1a-6a9dc89fdf12" />

The third visualization provides a deeper drill-down at the city level. In this view, the focus is on Houston, allowing for a detailed examination of its sales and profit performance. Houston’s losses are driven primarily by Binders (–$6,895) and Appliances (–$2,887), with additional negative contributions from Chairs, Bookcases, and Tables. These underperforming subcategories explain the city’s overall –$10,154 profit.<br>
<img width="1638" height="830" alt="City of Houston" src="https://github.com/user-attachments/assets/7a57abff-35a7-4372-ab60-0cfb652f1ee5" />

## Key findings

•	The business generated $2.29M in total sales and $286K in profit, resulting in a 12% overall profit margin, indicating healthy national performance despite localized losses.<br>
•	Technology is the top-performing category, contributing $145,455 in profit (51%), driven mainly by Phones ($44,516) and Binders ($30,222).<br>
•	Office Supplies is the second-largest profit driver at $122,491 (43%), with strong contributions from Paper ($34,054) and Storage ($21,279).<br>
•	Furniture shows the weakest performance, contributing only $18,451 (6%), with major losses in Tables (–$17,725) and Bookcases (–$3,473), despite strong profit from Chairs (+$26,590).<br>
•	Texas stands out as the largest loss-generating state, clearly visible on the map, indicating a significant regional performance issue.<br>
•	The sales trend shows steady growth with major spikes after 2024, suggesting improving demand and market expansion toward 2026.<br>
•	A total of 296 product returns indicates a meaningful impact on net profitability and highlights potential quality or fulfillment issues.<br>

## Limitations of the analysis
•	The dataset does not include actual operating costs, which limits full profitability modeling.<br>
•	Promotional timing and seasonality effects ae not fully captured.<br>
•	Customer behavior factors such as loyalty and lifetime value are not available.<br>

## Conclusion 
The analysis shows that while several states generate strong, consistent profits, ten states are currently operating at a net loss, pointing to underlying inefficiencies in pricing, discounting, shipping, or operating costs. Profitability varies significantly by region, indicating that a one-size-fits-all national strategy is no longer effective and that performance can be improved through customized, region-specific approaches. In addition, certain product subcategories continue to underperform, suggesting the need for revised sales strategies, tighter inventory control, or potential product line reductions. Overall, the data highlights clear opportunities for the company to protect its strongest markets, correct inefficiencies in weaker regions, and realign product strategy to maximize long-term profitability.

## Reccomendations
1.Adopt region-specific pricing and promotion strategies for the ten loss-generating states to address local cost structures, discount patterns, and customer behavior instead of relying on a single national strategy.

2.Reevaluate low-performing product subcategories by either adjusting pricing, reducing inventory levels, renegotiating supplier costs, or discontinuing consistently unprofitable items.

3.Double down on high-margin categories such as Technology and strong Office Supplies items by increasing inventory, marketing focus, and targeted promotions to maximize profitable growth.

4.Monitor return trends closely, as returns directly reduce net profit and may signal quality, fulfillment, or customer expectation issues.
