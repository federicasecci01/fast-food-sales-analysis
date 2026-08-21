🇬🇧 English | 🇮🇹 [Italiano](README_IT.md)


# Fast Food Sales Analysis

**Excel & Tableau project focused on sales performance, descriptive statistics and interactive data visualization.**

This project started from a dataset used in a free Excel course and became an opportunity to apply my **Mathematics background to a practical data analysis problem**.

I used **Excel** to clean and explore the data, build Pivot Tables and perform descriptive analysis. I then moved to **Tableau** to create an interactive dashboard that makes it possible to explore sales performance by manager, product and time period.

---

## What I wanted to find out

I approached the dataset by turning it into a set of questions:

* How much revenue did the company generate?
* How many units were sold?
* Which products generated the most revenue?
* How did sales change between November and December?
* How was revenue distributed among managers?
* Which payment methods and purchase channels generated the most revenue?
* How did product performance change when looking at each manager individually?

These questions guided both the Excel analysis and the final dashboard.

---

## From raw data to analysis

I first worked on the dataset in **Excel**, where I cleaned and organized the data before starting the analysis.

I used **Pivot Tables** to compare revenue and quantities across products, managers, payment methods and purchase channels.

I also used **descriptive statistics** to better understand the numerical variables in the dataset.

My Mathematics background helped me approach this part of the project with a quantitative mindset: rather than looking at individual values, I focused on **aggregations, comparisons, distributions and relationships between different dimensions of the data**.

---
## Outlier Analysis

As part of the exploratory analysis in Excel, I used a **box plot to identify potential outliers** in the numerical data.

I would not remove these observations automatically. In a real business environment, I would first investigate their origin by checking the underlying transaction and, when necessary, discussing the case with the **manager responsible for the related sales activity**.

The goal would be to understand whether the unusual value represents:

* a valid but exceptional transaction;
* a specific promotion or business event;
* a data-entry or recording error;
* or another operational factor.

Only after understanding the cause would I decide how to handle the observation in the analysis. Valid extreme values would generally be retained, while confirmed data-quality issues would be corrected or excluded with the decision properly documented.

---

## Tableau Dashboard

After completing the analysis in Excel, I used **Tableau** to turn the results into an interactive dashboard.

![Fast Food Sales Dashboard](dashboard_preview.png)

The dashboard tracks:

* Total Revenue
* Total Units Sold
* Revenue by Product
* Units Sold by Product
* Revenue by Manager
* Revenue by Payment Method
* Revenue by Purchase Location
* Monthly Revenue Trend

The **Manager** and **Date** filters update the analysis dynamically, making it possible to move from the overall company performance to a more specific view.

### 🔗 [Explore the interactive dashboard on Tableau Public](https://public.tableau.com/app/profile/federica.secci5789/viz/DashboardFastFood_17870511316250/Dashboard1)

---

## A quick look at the data

For the complete period analysed:

**Total Revenue:** €812,135
**Total Units Sold:** 118,539

The dashboard can then be used to move beyond these overall figures and compare performance across different products, managers, payment methods and periods.

---

## Tools & Skills

**Excel**

* Data Cleaning
* Pivot Tables
* Descriptive Statistics
* Data Aggregation
* Exploratory Data Analysis

**Tableau**

* Interactive Dashboards
* KPI Visualization
* Filters
* Data Visualization

**Quantitative approach**

* Descriptive Analysis
* Quantitative Reasoning
* Comparative Analysis
* Data Interpretation

---

## Repository

| File                            | Description                                                 |
| ------------------------------- | ----------------------------------------------------------- |
| `fast_food_sales_analysis.xlsx` | Excel workbook containing the data preparation and analysis |
| `fast_food_sales_dashboard.twb` | Tableau workbook                                            |
| `dashboard_preview.png`         | Preview of the interactive dashboard                        |

---

## Dataset

The dataset comes from the free Excel tutorial **“Master Data Analysis on Excel in Just 10 Minutes” by Kenji Explains** and is used here for educational and portfolio purposes.

I used the original dataset as a starting point to practice the analytical workflow and extend the work into an interactive Tableau project.

[Original YouTube tutorial](https://www.youtube.com/watch?v=_g5roKHj95o)

---

### Why this project?

As a **Mathematics graduate moving into Data Analytics**, I wanted this project to be more than an exercise in using Excel or Tableau.

It gave me the opportunity to take a dataset, ask questions about it, analyse the numbers and decide how to communicate the results clearly — connecting the quantitative way of thinking developed during my Mathematics degree with practical data analysis tools.
