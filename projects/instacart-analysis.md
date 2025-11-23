---
title: "Instacart Grocery Basket Analysis"
layout: single
sidebar:
  nav: "navigation"
excerpt: "Conducted data wrangling, quality checks, EDA, and visualizations in order to identify sales trends to inform targeted marketing strategies."
permalink: /projects/instacart-analysis/
---

## Overview
As an analyst for Instacart, an online grocery store that operates through an app, the objective is to uncover more information about their sales patterns to build a targeted marketing strategy. This analysis explores some of Instacart's data in order to derive insights and suggest strategies for better segmentation.

## Skills Used
<ul>
  <li>Practiced coding using basic Python data types (integers, floats, strings, booleans, lists, dictionaries).</li>
  <li>Conducted exploratory data analysis (EDA), including descriptive statistics and data inspection.</li>
  <li>Performed data wrangling, including renaming columns, changing data types, and subsetting datasets.</li>
  <li>Created new DataFrames based on filtering criteria.</li>
  <li>Answered analytical questions by summarizing user activity frequencies.</li>
  <li>Ensured data consistency by fixing mixed-type variables, handling missing values, and removing duplicates.</li>
</ul>

## Key Findings
<ul>
  <li>Most orders come through during the 11:00 to 15:00 hours of the day. Instacart can expect to be busiest during those timeframes and should aim to schedule ads during the hours of 0:00 - 10:00 and 16:00 - 24:00.</li>
  <li>Weekend shopping is the most popular.</li>
  <li>Regular customers are the primary customer at Instacart.</li>
  <li>There is no connection between dependents and age.</li>
  <li>More products are bought in the Mid-Range category (price is greater than 5, and less than or equal to 15).</li>
  <li>Department_id 4 (Produce) has the highest frequency of product orders, followed by department_id 16 (Dairy Eggs).</li>
</ul>

## Visuals
![What’s the distribution among users in regards to their brand loyalty (i.e., how often do they return to Instacart)?](https://rebeccameyer11.github.io/rebeccameyer/assets/images/IC_LoyaltyFlag.png)

*Figure 1: From this chart, you can see that regular customers are the primary customer at Instacart.*

![What are the busiest days of the week for Instacart?](https://rebeccameyer11.github.io/rebeccameyer/assets/images/IC_bar_orders_dow.png)

*Figure 2: Weekend shopping is the most popular. (0 = Saturday and 1 = Sunday)*

![What is the busist hour of the day at Instacart?](https://rebeccameyer11.github.io/rebeccameyer/assets/images/IC_order_hour_of_day.png)

*Figure 3: Most orders come through during the 11:00 to 15:00 hours of the day. Instacart can expect to be busiest during those timeframes and should aim to schedule ads during the hours of 0:00 - 10:00 and 16:00 - 24:00.*

## Final Deliverable
- <a href="https://github.com/rebeccameyer11/InstacartDataAnalysis/tree/main">GitHub Repo</a><br>
