# Global eCommerce Sales Analysis
![Teko banner](https://github.com/user-attachments/assets/b9f654a0-9afe-4bce-b032-97aaec142bf2)

## The goal of this analysis is to evaluate sales performance through the COVID-19 period (2019-2022), delivering insights on key revenue drivers and actionable recommendations for Operations, Sales, and Marketing leadership teams.


# Project Background
**Company Bio**

Teko Electronics has been a prominent player in the consumer electronics retail space since its founding in 2012. As a specialized e-commerce retailer based in the United States with a growing international consumer base, the business focuses exclusively on high-demand technology products, positioning itself as the go-to destination for premium electronics including laptops, mobile accessories, and gaming peripherals.
The business operates on a direct-to-consumer model through its proprietary e-commerce platform, with customer acquisition driven through diversified marketing channels. Unlike other large electronics retailers, Teko Electronics has carved out a niche by curating a focused product portfolio of premium technology items that appeal to professionals, gamers, and technology enthusiasts.

**Stakeholder Request**

Leadership requested this analysis in Q1 2023 to understand how the COVID-19 pandemic impacted sales performance from 2019-2022. The period represents a critical inflection point for technology retailers, with dramatic shifts in consumer behavior, supply chain disruptions, and evolving work-from-home requirements.

Understanding these performance patterns will inform strategic planning for the year, including loyalty program investment, marketing allocation, and potential product line expansion decisions. The insights from this analysis will be particularly valuable as we navigate the post-pandemic market normalization and prepare for potential future disruptions.

Insights and recommendations are provided on the following key areas:

- **Revenue Trends and Growth Analysis:** Overall sales performance, monthly and yearly growth rates, and key inflection points
- **Financial Performance Metrics:** Analysis of refund rates, AoV, and their impact on profitability across product categories
- **Loyalty Program Performance:** Evaluation of the new loyalty program's impact on repeat purchases and revenue contribution

The SQL queries used to inspect and clean the data for this analysis can be found here [link].

Targeted SQL queries regarding various business questions can be found here [link].

An interactive Tableau dashboard used to report and explore sales trends can be found here [link].


# Executive Summary

### Overview of Findings

Explain the overarching findings, trends, and themes in 2-3 sentences here. This section should address the question: "If a stakeholder were to take away 3 main insights from your project, what are the most important things they should know?" You can put yourself in the shoes of a specific stakeholder - for example, a marketing manager or finance director - to think creatively about this section.

[Visualization, including a graph of overall trends or snapshot of a dashboard]


# Insights Deep Dive
### Revenue Trends and Growth Analysis
Overall sales performance, monthly and yearly growth rates, and key inflection points.
  
* **2020 was the best performing year over the 2019-2022 time period**, generating over $10M in revenue. The top selling products - Gaming Monitor, Apple Airpods, and Macbook Air - collectively drove over 80% of sales that year.
  
* **Annual revenue growth peaked between 2019-2020 at 163%**, likely driven by pandemic-induced demand for remote work technology. Macbook Air and ThinkPad laptops experienced the highest individual product growth rates at 384% and 222% respectively.

* **Revenue peaked in December 2020 at just over $1.2M**, representing our highest single-month performance during the analysis period.
  
* **The largest monthly growth spike was from February 2020 to March 2020**, coinciding with inital COVID lockdowns, with all products experiencing revenue increases during this period.

* **Revenue declined sharply in 2021-2022 with a 46% drop**, reaching an all-time low of $178K in October 2022, suggesting market normalization post-pandemic.

* **Revenue consistently declined month-over-month after December 2020**, with the only exceoptions being seasonal holiday upticks in Novmeber and December of subsequent years.

  
![image](https://github.com/user-attachments/assets/ef8e2c5b-a6f7-4a64-8a0e-92f4aec0e14f)

![image](https://github.com/user-attachments/assets/95cb0d89-7bc9-458c-9ed3-98ad69624ebc)


### Financial Performance Metrics
Analysis of refund rates, AoV, and their impact on profitability across product categories.

* **Main insight 1.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 2.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 3.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.
  
* **Main insight 4.** More detail about the supporting analysis about this insight, including time frames, quantitative values, and observations about trends.

[Visualization specific to category 3]


### Loyalty Program Performance
Evaluation of the new loyalty program's impact on repeat purchases and revenue contribution.

* **Non-loyalty customers outperformed loyalty customers**, with 13% higher average order value and comprising 61% of total sales during the analysis period, suggesting the program may not be effectively incentivizing higher spending.
  
* **Revenue from loyalty customers has steadily declined over the past 12 months**, despite a modest upward trend in their average order value, indicating fewer loyalty customers are making purchases overall.
  
* **Active loyalty customer participation is decreasing**, with non-loyalty customers placing more orders than loyalty customers in the past 4 months, raising questions about program engagement and value proposition.
  
* **The loyalty program shows minimal impact on repeat purchase behavior**, with only a 2 percentage point difference between loyalty customers (15%) and non-loyalty customers (13%) placing more than one order.

[Visualization specific to category 2]



# Recommendations

Based on the insights and findings above, we would recommend the [stakeholder team] to consider the following: 

* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  
* Specific observation that is related to a recommended action. **Recommendation or general guidance based on this observation.**
  

# Data Structure & Initial Checks

The company's main database structure consists of the following four tables:
- **customers:** Details about the creation fo the customer's account
- **geo_lookup:** Reference of countries and their respective region
- **order_status:** Dates for the various statuses of each order
- **orders:** Product and price information for each order


# Assumptions and Caveats

Throughout the analysis, multiple assumptions were made to manage challenges with the data. These assumptions and caveats are noted below:

* Orders with $0 transaction prices is missing data and not customers who received products for free
  
* Fluctuations in pricing within individual products were purchases made with coupons or special discounts and not changes in retail pricing
  
* Mismatches between currency and country per customer was due to customers purchasing items in a different currency than where they are located

