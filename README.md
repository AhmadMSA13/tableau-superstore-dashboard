# Tableau-Superstore-Dashboard

---

## 🔗 Access the Dashboard

* 📊 **Interactive Tableau Dashboard:**
  👉 [Click here to view the live dashboard on Tableau Public](https://public.tableau.com/views/SuperstoreDashboard_17531850841620/SuperstoreDashboard?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
 
* 📄 **Dashboard Report (PDF format):**
  👉 [Download the PDF version here](Superstore%20Dashboard.pdf.pdf)

---

## 1. Background and Overview

This personal project analyzes sales performance data from a retail superstore operating in the United States between January 2014 and December 2017. This interactive dashboard, it provides insight into sales trends, customer segments, regional breakdowns, product categories, and profitability.

The purpose of this project is to:

* Monitor monthly sales and profit trends
* Understand regional and state-level performance
* Identify high-performing categories and cities
* Support decision-making with dynamic and visual insights

---

## 2. Data Structure Overview

The dataset includes a complete record of transactional data from the superstore, structured as follows:

| Column Name     | Description                                               |
| --------------- | --------------------------------------------------------- |
| `Row ID`        | Unique identifier for each row                            |
| `Order ID`      | Unique identifier for each customer order                 |
| `Order Date`    | Date when the order was placed                            |
| `Ship Date`     | Date when the order was shipped                           |
| `Ship Mode`     | Shipping method used (Standard, First Class, etc.)        |
| `Customer ID`   | Unique identifier for each customer                       |
| `Customer Name` | Customer's full name                                      |
| `Segment`       | Customer segment: Consumer, Corporate, or Home Office     |
| `Country`       | Country of the customer (mainly United States)            |
| `City`, `State` | Location details of the order                             |
| `Postal Code`   | ZIP code of the shipping address                          |
| `Region`        | U.S. business region (West, East, South, Central)         |
| `Product ID`    | Unique identifier for the product                         |
| `Category`      | Product category (Furniture, Office Supplies, Technology) |
| `Sub-Category`  | Subdivision of each category                              |
| `Product Name`  | Name of the product                                       |
| `Sales`         | Revenue from the transaction                              |
| `Quantity`      | Number of units sold                                      |
| `Discount`      | Discount applied on the sale                              |
| `Profit`        | Profit from the transaction                               |

---


## 3. Executive Summary

**Key Highlights:**

* **Total Sales (All States & Cities):** \$2,297,201
* **Total Profit:** \$286,397
* **Total Quantity Sold:** 37,873 units
* **Top States by Sales:**

  * California: \$457,688
  * New York: \$310,876
  * Texas: \$170,188
  * Washington: \$138,641
* **Sales by Category:**

  * Technology: \$836,154
  * Office Supplies: \$791,047
  * Furniture: \$742,000
* **Category Quantity Share:**

  * Office Supplies: 60.48%
  * Furniture: 21.20%
  * Technology: 18.32%

---

## 4. Insight Deep Dive

### a. Sales Trend Analysis (2014–2017)

* **Sales were highly fluctuating** throughout the 4-year period.
* Major **sales spikes** occurred, such as one reaching **\$118,448**, following a previous high of **\$96,999**.
* The **lowest recorded drop** reached **\$4,520**, indicating severe inconsistencies in revenue flow, possibly due to seasonal or promotional factors.

### b. State and City Performance

* **California** is the dominant contributor to total sales, making up over **19%** of total sales alone.
* **New York and Texas** follow, while **Washington** also shows solid performance.
* Profitability across states varies, highlighting opportunities for strategic regional marketing.

### c. Category Analysis

* **Technology** generates the **highest revenue**, but contributes the **lowest share of units sold**.
* **Office Supplies** dominate in quantity (60.48%) but yield less profit per item, suggesting lower margins.
* **Furniture** sits in the middle range in both sales and quantity.

### d. Product and Segment Strategy

* Further filtering by **Segment** (Consumer, Corporate, Home Office) can reveal customer buying behavior and value.
* Profitability is often diluted by **high discount rates**, especially in Furniture, suggesting a need to evaluate pricing strategies.

---
