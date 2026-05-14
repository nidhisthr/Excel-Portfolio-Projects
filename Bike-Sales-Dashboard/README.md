# Bike Sales Analysis Dashboard

## Project Description
This project analyzes customer purchase behavior for a bike company. By processing a dataset of 1,000 customers, I identified key factors—such as income, age, and commute distance—that correlate with a customer's decision to buy a bike.

## Dashboard Preview
<img width="1919" height="1079" alt="Screenshot 2026-05-14 191930" src="https://github.com/user-attachments/assets/3876b72a-04e3-46af-9520-abc6e9e9ce74" />


## Data Workflow

### 1. Data Cleaning (`bike_buyers` tab)
* Removed duplicate entries to ensure data accuracy.
* Standardized the **Commute Distance** column for better grouping.
* Created an **Age Brackets** column using a nested `IF` formula to group customers into:
  * **Adolescent** (<31)
  * **Middle Age** (31-54)
  * **Old** (55+)

### 2. Data Processing (`Pivot Table` tab)
* Built multiple Pivot Tables to summarize:
  * Average Income per purchase filtered by Gender.
  * Count of purchases categorized by Age Brackets.
  * Customer commute trends.

### 3. Interactive Dashboard (`Dashboard` tab)
* Designed a clean, professional layout.
* Added **Slicers** (Gender, Region, Education) to allow users to filter the entire dashboard dynamically.

## Key Findings
* **The "Sweet Spot" Age:** The **Middle Age (31-54)** group is the most active buyer segment.
* **Commute Sensitivity:** People with a **0-1 Mile** commute are the most likely to purchase a bike, suggesting bikes are used for short-distance travel or local exercise.
* **Income Trend:** On average, customers who purchased a bike had a higher income than those who did not.

## Files in this Folder
* `Bike_Sales_Dashboard.xlsx`: The full interactive Excel workbook.
* `dashboard_preview.png`: High-resolution screenshot of the final dashboard.
