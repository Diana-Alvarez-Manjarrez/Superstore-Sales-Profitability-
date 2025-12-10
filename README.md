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
•	While some states consistently generate strong profits, several others operate at a net loss, indicating inefficiencies in pricing or operating costs.<br>
•	Profitability varies significantly by region suggesting the need for customized regional strategies rather than single nationwide approach.<br>
•	10 states are operating at a loss.<br>
•	Certain product sub categories perform poorly suggesting the need for a better sales strategy or cutback on inventory for that product.<br>

## Limitations of the analysis
•	The dataset does not include actual operating costs, which limits full profitability modeling.<br>
•	Promotional timing and seasonality effects ae not fully captured.<br>
•	Customer behavior factors such as loyalty and lifetime value are not available.<br>
