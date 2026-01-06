## Bike Sales Analysis Project

### Project Overview

This project involves transforming raw survey data into an interactive Excel dashboard. The goal is to identify key demographic trends and purchasing patterns to understand what drives a customer to buy a bike.

### Dataset Description

The dataset contains a variety of customer attributes, including:

* **ID & Demographics:** Marital Status, Gender, Income, Children, Education, Occupation.
* **Logistics:** Home Owner, Cars, Commute Distance, Region, Age.
* **Target Variable:** Purchased Bike (Yes/No).

---

### Workflow

#### 1. Data Cleaning

Before analysis, the "Raw Data" was processed in a separate sheet to ensure accuracy:

* **Duplicates:** Removed duplicate entries based on Customer ID.
* **Standardization:** * Changed "M" to "Married" and "S" to "Single" in the Marital Status column.
* Changed "M" to "Male" and "F" to "Female" in the Gender column.


* **Data Formatting:** Converted the Income column to Currency.
* **Custom Columns:** Created an **Age Brackets** column using a nested `IF` statement:
* `30 & under`
* `31-54`
* `55+`



#### 2. Pivot Tables & Analysis

Three primary areas were explored to find correlations with bike purchases:

1. **Income vs. Purchase:** Average income of customers who bought vs. didn't buy, categorized by gender.
2. **Commute Distance:** How the length of a commute impacts the likelihood of a bike purchase.
3. **Customer Age:** Identifying which age bracket is the most active in the market.

#### 3. Interactive Dashboard

The final dashboard provides a visual summary of the findings, featuring:

* **Slicers:** Interactive filters for Region, Education, and Marital Status.
* **Bar & Line Charts:** Visual representations of the pivot table data for quick insights.

---

### Key Insights

* **Income Matters:** On average, customers who purchased bikes had a higher income than those who did not.
* **Commute Sweet Spot:** Customers with a commute of 0–1 miles are significantly more likely to purchase a bike.
* **Demographic Peak:** The "Middle Aged" bracket (31–54) represents the largest portion of bike buyers.

---

### How to Use

1. **Download:** Clone this repository or download the `.xlsx` file.
2. **Explore:** Navigate to the `Dashboard` sheet to interact with the slicers.
3. **Review:** Check the `Pivot Table` to see the underlying pivot tables and the `Working Sheet` sheet for the processed dataset.

> **Note:** This project was completed as part of the Alex the Analyst Excel Portfolio series.
