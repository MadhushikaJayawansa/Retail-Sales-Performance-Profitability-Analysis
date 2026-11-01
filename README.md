# Retail-Sales-Performance-Profitability-Analysis

## Executive Summary

A multi-market retail business needs to understand how effectively it generates revenue and maintains profitability across its products, markets and customer segments.

This project investigates retail sales performance using transaction data covering six countries from January 2011 to July 2016. The analysis examines revenue generation, product performance, geographical differences, customer segments and changes in profitability over time.

The business recorded approximately 85.27 million in revenue and 32.22 million in profit, representing an overall profit margin of approximately 37.8%.

As the Data Analyst in this project, my objective is to identify the factors contributing to business performance, highlight areas requiring management attention and translate the findings into practical recommendations.


## Business Context

The business operates across six international markets: the United States, Australia, the United Kingdom, Germany, France and Canada. Its product portfolio includes three main categories: Bikes, Accessories and Clothing.

Operating across different markets and product categories creates a need to understand where sales are generated, which products contribute most to profitability and how customer purchasing patterns vary.

Although overall sales provide an indication of business performance, revenue alone does not explain whether the business is generating sustainable profit or which areas deserve greater management attention.

Management therefore needs a clearer view of performance across geographical markets, products, customers and time periods to support better commercial decisions.

## Business Problem

The retailer operates across multiple countries and product categories, but overall sales figures alone do not provide enough information to understand its commercial performance.

Management needs to identify which markets and products generate the greatest revenue and profit, whether profitability is consistent across geographical regions, and how performance changes over time.

Without a clear understanding of these differences, it becomes difficult to identify underperforming areas, recognise growth opportunities and prioritise business resources.

As the Data Analyst, I aim to investigate these performance differences and provide insights that can support more informed business decisions.

## Project Objectives

- Evaluate overall sales performance using revenue, profit and profit margin.
- Identify the countries and regions contributing most to revenue and profitability.
- Assess product category and individual product performance.
- Examine changes in revenue, costs and profitability over time.
- Understand sales contributions across different age groups and genders.
- Translate analytical findings into practical business recommendations.

## Business Questions & Key Performance Indicators

The analysis is guided by the following business questions:

| Business Question | Supporting Metrics | Business Purpose |
|---|---|---|
| How is the business performing overall? | Revenue, Profit, Profit Margin, Units Sold | Evaluate overall commercial performance. |
| Which markets contribute most to business performance? | Revenue, Profit, Profit Margin by Country and State | Identify strong markets and geographical differences. |
| Which products drive revenue and profitability? | Revenue and Profit by Category, Subcategory and Product | Understand product contributions and identify opportunities. |
| How has business performance changed over time? | Monthly Revenue, Cost, Profit and Profit Margin | Identify trends and changes in financial performance. |
| Which customer segments contribute most to sales? | Revenue by Age Group and Gender | Understand differences in customer sales contributions. |

### North Star Metrics

The three primary measures used to evaluate business performance are:

- **Revenue:** The total value of sales generated.
- **Profit:** Revenue remaining after deducting recorded costs.
- **Profit Margin:** The proportion of revenue retained as profit, calculated as Profit ÷ Revenue × 100.

Supporting KPIs, including units sold and cost, provide additional context for understanding sales volume and financial performance.

## Visual Analysis

### Monthly Revenue by Year

### Revenue Accelerated in the Second Half of 2013 and 2015, Reaching a Record 3.85 Million in December 2015

<img src="Charts/TIME_Heatmap_Revenue.png">

The monthly revenue heatmap reveals substantial differences in sales performance across the analysed years, with particularly strong revenue growth during the second half of 2013 and 2015.

In 2013, monthly revenue increased from **1.23 million in July to 3.00 million in December**. A similar pattern occurred in 2015, when revenue rose from **666,938 in January to 3.85 million in December**, the highest monthly revenue recorded in the dataset.

December also recorded relatively strong revenue in the other complete years displayed, reaching 1.13 million in 2011 and 1.11 million in 2012.

However, this growth pattern was not consistent throughout the dataset. In 2014, revenue was relatively high during the first six months, reaching 2.79 million in June, before dropping to 516,887 in July. Revenue increased again in the following year, particularly during the second half of 2015.

**Business Insight**

The repeated increase in December revenue across the complete years suggests that year-end sales periods may be important contributors to overall business performance. The substantial increases observed during the second half of 2013 and 2015 also highlight the need to understand what drove these changes rather than assuming they were caused by seasonal demand alone.

**So What?**

Management could investigate the sales activities, product performance and market contributions associated with these high-revenue periods. Understanding the factors behind these increases could help improve inventory planning, promotional timing and resource allocation during important sales periods.

### Revenue by Country

### The United States and Australia Generate Nearly 58% of Total Revenue

<img src="Charts/Revenue by Country.png">

The geographical revenue analysis reveals a significant concentration of sales in two markets: the United States and Australia.

The **United States leads with 27.98 million in revenue**, contributing approximately **32.8%** of total business revenue. Australia follows with **21.30 million**, representing approximately **25.0%**. Combined, these two markets account for approximately **57.8% of total revenue**.

The remaining four countries contribute considerably less. The United Kingdom generates 10.65 million, followed by Germany at 8.98 million, France at 8.43 million and Canada at 7.94 million.

The difference between the highest and lowest performing markets is substantial. Revenue from the United States is approximately **3.5 times higher than Canada's**.

**Business Insight**

The revenue distribution indicates that the retailer's sales performance is concentrated in the United States and Australia. While these markets provide a strong revenue base, the smaller contributions from the other four countries highlight differences in geographical sales performance. However, revenue alone does not establish which markets are more profitable.

**So What?**

Management should continue monitoring the United States and Australian markets because changes in their sales performance could have a considerable effect on overall revenue. At the same time, the business could investigate growth opportunities in the United Kingdom, Germany, France and Canada by examining regional demand, product preferences and profitability before making expansion or investment decisions.

### Revenue vs Profit Margin by State

### High-Revenue States Do Not Always Deliver the Highest Profit Margins

<img src="Charts/GEO_Scatter_State.png">

The state-level performance analysis compares revenue and profit margin to evaluate whether the regions generating the highest sales are also retaining a greater proportion of revenue as profit.

A four-quadrant scatter plot was used to examine three dimensions simultaneously: revenue, profit margin and order quantity. Median benchmarks of approximately **1.7 million in revenue** and **39% profit margin** divide the states into four performance groups.

The analysis highlights an important difference between sales scale and profitability. The highest-revenue state generated approximately **17.6 million in revenue**, with a profit margin of around **44%** and an order volume of approximately **270,000 units**.

However, another high-volume state generated approximately **7.9 million in revenue** while achieving a profit margin of around **47%**, demonstrating that a region with lower revenue can retain a greater proportion of its sales as profit.

In contrast, several states generating between **5 million and 9.2 million in revenue** recorded profit margins below 35%, indicating that relatively strong sales do not necessarily translate into equally strong profitability.

**Business Insight**

The findings reveal differences in how effectively geographical markets convert revenue into profit. Some high-revenue states combine substantial sales volume with healthy margins, while other regions generate considerable revenue but retain a smaller proportion as profit. This suggests that evaluating geographical performance through revenue alone could overlook important differences in profitability.

**So What?**

Management should investigate the product mix, pricing and cost structures of high-revenue, lower-margin states to identify opportunities for improving profitability. The higher-margin state could also provide a useful comparison for understanding differences in product and sales performance. These investigations should take place before assuming that increasing sales volume will automatically improve financial performance.


### Product Performance

#### Bikes Dominate Revenue, but Product Rankings Reveal Different Profit Contributors

<!-- Top Image: Full Width -->
<p align="center">
  <img src="Charts/Revenue by Product Category.png" alt="Revenue by Product Category" width="100%">
</p>

<!-- Bottom Two Images: Side by Side (Left and Right) -->
<table>
  <tr>
    <td width="50%" align="center">
      <img src="Charts/Top 5 Products by Revenue.png" alt="Top 5 Products by Revenue" width="100%">
      <br>
      <sub><b>Top 5 Products by Revenue</b></sub>
    </td>
    <td width="50%" align="center">
      <img src="Charts/Top 5 Products by Profit.png" alt="Top 5 Products by Profit" width="100%">
      <br>
      <sub><b>Top 5 Products by Profit</b></sub>
    </td>
  </tr>
</table>

Bikes dominate the product portfolio, generating 61.78M (72.5%) of total revenue, compared with 15.12M (17.7%) from Accessories and 8.37M (9.8%) from Clothing. This indicates that overall sales performance is heavily dependent on the bicycle category.

However, comparing the top five products by revenue and profit reveals an important difference. Road-150 Red, 62 is the highest revenue-generating product at 3.83M, but it ranks second in profit at 1.24M. In contrast, Mountain-200 Black, 38 generates 3.37M in revenue but ranks first in profit at 1.31M. Its higher profit contribution relative to its revenue suggests a stronger profit margin than the Road-150 Red, 62. This demonstrates that the products generating the most sales do not always generate the most profit.

Another notable finding is the presence of Sport-100 Helmet, Red among the five most profitable products, contributing 1.19M in profit. Although bicycles dominate total category revenue, this result highlights the contribution that individual accessories can make to overall profitability.

**Business Implications and Recommendations**

The business should avoid evaluating product success through revenue alone. The difference between the leading revenue and profit contributors highlights the importance of monitoring product-level profitability alongside sales performance. Management should review the costs and margins of high-revenue products, maintain appropriate stock levels for consistently profitable bicycle models, and investigate opportunities to increase accessory sales. Targeted bicycle-and-helmet bundles could also be tested to assess whether they encourage additional purchases and improve overall order profitability.


### Profitability Trend Analysis

#### Profit Margins Reached Approximately 51% at Two Points, but the Improvements Were Not Sustained

<p align="center">
  <img src="Charts/Profit Margin Timeline.png" alt="Profit Margin Timeline" width="100%">
</p>

The monthly profit margin trend shows that profitability was relatively stable at approximately 31.5%–33.5% from late 2010 to mid-2013. This pattern changed around mid-2013, when margins increased to approximately 42.5%, followed by a peak of around 51% in mid-2014. However, this improvement was temporary, with margins subsequently returning to approximately 32.5%–33.5%.

A similar pattern appeared between late 2015 and mid-2016. Profit margins increased to approximately 39%–41%, before reaching another peak of around 51%. These movements indicate that the business experienced periods of stronger profitability, but the higher margins were not consistently maintained.

**Business Implications and Recommendations**

The temporary increases in profit margin suggest opportunities to investigate which products, pricing changes or cost movements contributed to stronger profitability during these periods. Management should compare product mix, selling prices and costs during peak-margin months against more typical periods. Understanding these differences could help identify practices worth maintaining and areas where profitability can be improved more consistently.


## 5. Key Business Insights

The analysis revealed several important patterns in the retailer's sales and profitability performance.

### 1. Revenue Is Concentrated in Two Major Markets

The United States generated 27.98M (32.8%) of total revenue, while Australia contributed 21.30M (25.0%). Together, these two markets accounted for approximately 57.8% of total revenue.

This indicates a considerable reliance on these markets for sales performance. Although the remaining four countries contribute to the business, their individual revenue levels are substantially lower. This makes the performance of the United States and Australia particularly important to overall revenue.

### 2. Bikes Dominate Revenue, but Revenue and Profit Rankings Differ

Bikes generated 61.78M, representing 72.5% of total revenue. At the individual product level, Road-150 Red, 62 was the leading revenue contributor at 3.83M. However, Mountain-200 Black, 38 ranked first in profit at 1.31M.

This difference demonstrates that the product generating the highest revenue does not necessarily generate the highest profit. The Sport-100 Helmet, Red also ranked among the five most profitable products, highlighting the contribution of accessories to overall profitability.

### 3. Revenue Growth Does Not Always Translate into Higher Profitability

In 2015, revenue increased by 41.49%, while profit increased by 28.38%. Over the same period, the profit margin declined from 41.43% in 2014 to 37.60% in 2015.

This indicates that although the business generated considerably more revenue in 2015, profit did not grow at the same rate. The decline in profit margin highlights the importance of monitoring costs and profitability alongside sales growth.

### 4. Profitability Varies Across Geographic Markets

The state-level analysis revealed differences in profitability across regions. British Columbia recorded a profit margin of approximately 46.88%, while Washington recorded approximately 29.63%. California also performed strongly, with a margin of approximately 43.98%.

These differences suggest that revenue performance alone does not provide a complete picture of regional performance. Comparing profit margins across states can help management identify regions that may require further investigation into product mix, pricing and costs.

### 5. Adult Customers Represent the Largest Revenue Segment

Customers aged 35–64 contributed approximately 42.58M, accounting for around 50% of total revenue. Young Adults (25–34) generated approximately 30.66M, making them the second-largest revenue segment.

Together, these two age groups account for a substantial share of sales. This provides a useful starting point for understanding the customer segments contributing most to revenue and evaluating opportunities for targeted marketing.

---

## 6. Business Recommendations

Based on the findings, the following actions could help management improve sales performance, monitor profitability and make more informed business decisions.

| Business Opportunity | Recommended Action | Expected Business Benefit |
|---|---|---|
| Dependence on the United States and Australia | Monitor sales performance in these major markets while investigating growth opportunities in the other four countries. | Support market development and reduce reliance on the two largest revenue contributors. |
| Differences between product revenue and profit | Evaluate products using both revenue and profit, and review the costs and margins of leading products. | Improve product selection and support more profitable sales decisions. |
| Declining profit margin despite revenue growth | Monitor monthly profit margins, product costs and changes in profitability alongside revenue. | Identify potential profitability issues earlier and support better cost management. |
| Regional profitability differences | Investigate product mix, pricing and cost differences in lower-margin states and compare them with stronger-performing regions. | Identify opportunities to improve regional profitability. |
| Concentration of revenue among adult customers | Use customer segment findings to evaluate targeted marketing campaigns and product offers for Adults and Young Adults. | Improve marketing relevance and identify opportunities to increase sales among important customer segments. |
| Contribution from profitable accessories | Test targeted bicycle-and-helmet bundle offers and monitor their effect on accessory sales and order profitability. | Explore opportunities to increase accessory purchases and overall profit contribution. |

These recommendations are proposed actions based on the observed patterns. Their actual impact should be evaluated through further analysis and business testing.


## 7. Technical Details

### Tools and Technologies

- **Python:** Data inspection, cleaning, preparation and validation using Pandas and NumPy.
- **Tableau:** Exploratory business analysis, KPI reporting, interactive dashboards and visual storytelling.
- **GitHub:** Project documentation, README presentation and portfolio sharing.

### Dataset Overview

The project uses a retail sales dataset on Kaggle containing 113,036 original records and 18 columns, covering January 2011 to July 2016.

 <a href="https://www.kaggle.com/datasets/sadiqshah/bike-sales-in-europe">Go to Dataset on Kaggle</a>

The dataset includes information about sales dates, products, product categories, customer demographics, geographic markets, order quantities, revenue, costs and profit.

### Data Preparation

- Inspected the dataset structure, data types, missing values and duplicate records.
- Removed 1,000 exact duplicate rows.
- Converted the date column into a datetime format.
- Reviewed categorical values and numerical fields for consistency.
- Prepared and validated the final cleaned dataset, containing 112,036 records and 18 columns.

### Analytical Methods

- Descriptive analysis of revenue, profit, costs and profit margins.
- Comparative analysis across countries, states, product categories and individual products.
- Monthly and yearly trend analysis.
- Customer segmentation by age group and gender.
- Profitability comparisons using profit margin and product-level performance.

**Key Metric:** Profit Margin = (Profit / Revenue) × 100

### Project Scope and Limitations

- The dataset does not contain a unique customer identifier, so customer retention, repeat purchases and customer lifetime value could not be measured.
- The analysis identifies patterns and relationships in historical sales data; it does not establish the causes behind those patterns.
- The dataset ends in July 2016, so 2016 represents a partial year and should not be directly compared with complete years.
- The original dataset's currency and source attribution should be verified before making currency-specific claims or publishing source credits.
- Recommendations are analytical proposals and require further investigation or testing before implementation.


## 8. Project Resources

Explore the complete project and supporting materials:

- **Interactive Tableau Dashboard:** [View the Live Dashboard](https://public.tableau.com/views/SalesIntelligence_17932751713960/05TrendsProfitability?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

- **Python Data Preparation Notebook:** [View the Google Colab Notebook](https://colab.research.google.com/drive/1sFuC_X9rQnSapmMHf_Af2jBsSvAP9Tyf?usp=sharing)

- **Cleaned Dataset:** [View the Cleaned Dataset](data\retail_sales_cleaned.csv)

The Tableau dashboard provides interactive views of sales performance, product profitability, geographic performance, trends and customer segments. The Google Colab notebook documents the Python-based data preparation and cleaning process.