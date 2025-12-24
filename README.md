# GameHub-Sales-Analysis

---
##  Table of Contents
- [Project Background](#project-background)
- [Initial Checks & Metrics](#initial-checks--metrics)
- [Executive Summary](#executive-summary)
- [Deep Dive Insights](#deep-dive-insights)
- [KPI, Insights & Recommendations](#kpi-insights--recommendations)
---

## **Project Background**

**GameHub**, established in **2013**, has rapidly grown into a global ecommerce platform offering a wide range of gaming products and accessories varying from flagship consoles to high-performance devices and premium peripherals. As the gaming retail landscape becomes increasingly competitive, GameHub continues to expand its operations, now approaching **90,000 customers** and surpassing **100,000 transactions**, with total revenue exceeding **$22 million**. The company’s rapid growth is supported by strong product demand, strategic scaling, and an improving digital retail experience.
<br/>

This project presents a comprehensive **data analysis of GameHub’s performance from 2019 to 2021**, reporting to the Head of Operations, using public dataset of 20,000+ sales records as a sample.It highlights customer trends, product performance, operational insights and recommendations to enhance professional decision-making and sustain GameHub’s long-term performance.

---
<br/>

## **Initial Checks & Metrics**

**GameHub** dataset contains **20,000+ gaming product sales records** from multiple countries spanning **2019–2021**. Before analysis, thorough quality checks were completed to validate data completeness, detect outliers, and ensure the dataset was suitable for utilization and performance analysis. The objective is to understand how **total revenue in USD** evolved across all products during this period. This initial assessment provides high-level revenue trends to support **product, marketing, and finance managers** in evaluating overall performance and guiding strategic decisions.
<br/>
* Stakeholders aim to understand **high-level sales trends and patterns**, with **USD revenue** as the main KPI.
* Analysis uses key columns: **usd_price**, **product_name**, and **purchase time**.
* **Core metrics include:**

  * **Total revenue by month**
  * **Average revenue**
  * **Product-level performance**
  * **Minimum, maximum, and outlier detection**
* Additional segmentation available by **region** and **user demographics** (e.g., marketing channels, account creation method) to uncover deeper insights.

---
<br/>

## **Executive Summary**

An analysis of GameHub’s sales data from **2019–2021** reveals total revenue of **$6.1 million**, with monthly performance ranging from **$80,000 to $500,000**. The data shows a noticeable upward trajectory beginning in **2020**, during which all products experienced strong sales growth. This overall trend highlights increasing demand and improved customer engagement across the platform.

Product-level insights indicate that **gaming monitors** were the top-performing item, generating nearly **$2 million** in total revenue. In contrast, **gaming headsets** performed significantly worse, contributing less than expected—suggesting possible data gaps that require verification. Across product categories, headsets were the weakest segment, accounting for **less than 2%** of total sales, signaling potential areas for product strategy review.

Seasonal patterns also emerged, with **December consistently showing major spikes in revenue**, likely driven by holiday shopping behavior or targeted promotions. A particularly strong surge occurred in **December 2020**, warranting further investigation into marketing activities during that period. These findings provide valuable guidance for the **finance**, **product**, and **marketing teams** to refine forecasting, strengthen category strategies, and optimize campaign planning.

---
<br/>

## **Deep Dive Insights**

* **1.Sales Momentum & Decline**

  * Sales **doubled in April 2020**, reaching all-time highs in **September and December 2020**.
  * A sharp **downturn followed in 2021**, indicating decreased demand or market normalization.
    
![Overall Sales](https://github.com/swetasunilan/GameHub-Sales-Analysis/blob/main/Data%20Viz/Overall%20Sales.png)

* **2.Product-Level Drivers**

  * **Gaming Monitor, Nintendo Switch, and Sony PlayStation** were the primary drivers behind both the earlier spike and the later decline.
  * All three products showed **plateauing behavior after late-2020 peaks**, contributing to overall sales dips.

![Sales by Month](https://github.com/swetasunilan/GameHub-Sales-Analysis/blob/main/Data%20Viz/Sales%20By%20Month.png)

* **Channel Dynamics**

  * **Direct traffic** is the dominant source of revenue, far outperforming all other marketing channels.
  * A major **drop in direct traffic for Gaming Monitors** occurred in early 2021, exceeding declines seen in other products.

![Top 3 Sales By Channels](https://github.com/swetasunilan/GameHub-Sales-Analysis/blob/main/Data%20Viz/Top%203%20Sales%20by%20Channels.png)

* **Regional Trends**

  * All regions showed **similar dips during 2020–2021**, pointing to broad **global or macroeconomic factors**.
  * The decline for **Gaming Monitors** was most pronounced in the **North America (NA)** region and within direct traffic, suggesting possible **competitor shifts, changing preferences, or market saturation**.
    
![Top 3 Sales By Region](https://github.com/swetasunilan/GameHub-Sales-Analysis/blob/main/Data%20Viz/Top%203%20Sales%20By%20Region.png)

---
<br/>

##  **KPI, Insights & Recommendations**

| **KPI**                    | **Detailed Insight**                                                                                                                                                                                                                                                          | **Recommendation**                                                                                                                                                 |
| ----------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Total Sales / Revenue**  | Sales **doubled in April 2020**, reaching **all-time highs in September and December 2020**. After this surge, revenue **declined sharply throughout 2021**, signaling a reversal in demand or market normalization.                                                             | Use historical spikes to forecast seasonal patterns. Launch early campaigns before peak months and create retention strategies to prevent post-peak declines.         |
| **Sales by Product**       | **Gaming Monitor, Nintendo Switch, and Sony PlayStation** were the major contributors to both the 2020 surge and the 2021 decline. All three showed **plateauing behavior after Sept & Dec 2020**, driving overall downturn.                                                     | Introduce bundles, upsells, or refreshed product messaging. Conduct deeper analysis to understand product fatigue and consider diversification within top categories. |
| **Sales by Channel**       | **Direct traffic overwhelmingly dominates revenue**, with all other channels performing significantly lower. A **major dip in Direct sales for Gaming Monitors** occurred in early 2021, larger than any other product or channel.                                               | Reduce over-reliance on Direct traffic by strengthening social, referral, and paid channels. Test channel-specific promotions to broaden acquisition sources.         |
| **Regional Sales Trends** | All regions show **similar dips in 2020–2021**, suggesting global or macroeconomic influence. However, the **Gaming Monitor decline is heavily concentrated in North America (NA) and Direct traffic**, indicating localized issues such as competition or shifting preferences. | Investigate NA-specific competitors, pricing dynamics, and consumer trends. Deploy targeted offers or partnerships in NA to recover lost share.                       |
| **Seasonal Trends**        | Peaks in **April, September, and December** highlight strong recurring seasonal behaviours. The **largest spikes occurred in 2020**, likely due to holiday demand or promotional activity.                                                    | Align marketing spend, inventory planning, and campaign launches with seasonal cycles. Expand promotional events around these months to maximize growth.              |

---

