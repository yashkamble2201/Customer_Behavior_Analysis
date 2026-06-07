# Customer Shopping Behavior Analysis

## Overview

This project analyzes customer shopping behavior using transactional data to uncover patterns in purchasing habits, customer demographics, product preferences, subscription trends, and revenue generation. The analysis combines Python, SQL, and Power BI to transform raw data into actionable business insights.

---

## Dataset

### Dataset Information

* **Total Records:** 3,900
* **Total Features:** 18
* **Domain:** Retail / E-Commerce Customer Analytics

### Key Attributes

* Customer Demographics (Age, Gender, Location)
* Subscription Status
* Product Category and Item Purchased
* Purchase Amount
* Season, Size, and Color
* Discount Applied
* Review Rating
* Shipping Type
* Previous Purchases
* Purchase Frequency

---

## Tools & Technologies

### Python

* Pandas
* NumPy
* Matplotlib
* Seaborn

### Database

* PostgreSQL
* SQL

### Business Intelligence

* Power BI

### Documentation & Presentation

* Microsoft Word
* Gamma AI

---

## Project Workflow

### 1. Data Loading

* Imported the dataset using Pandas.
* Examined dataset structure and data types.
* Generated summary statistics.

### 2. Exploratory Data Analysis (EDA)

* Analyzed customer demographics.
* Explored purchase behavior patterns.
* Identified trends across product categories.
* Visualized spending and subscription behavior.

### 3. Data Cleaning

* Handled missing values in review ratings.
* Standardized column names using snake_case.
* Removed redundant columns.
* Verified data consistency and quality.

### 4. Feature Engineering

Created new features such as:

* Age Groups
* Purchase Frequency Metrics
* Customer Segments

### 5. SQL Analysis

Loaded the cleaned dataset into PostgreSQL and performed business-focused analysis:

* Revenue by Gender
* High-Spending Discount Users
* Top Rated Products
* Shipping Type Comparison
* Subscriber vs Non-Subscriber Analysis
* Discount-Dependent Products
* Customer Segmentation
* Top Products by Category
* Repeat Buyers Analysis
* Revenue by Age Group

### 6. Power BI Dashboard

Developed an interactive dashboard to monitor:

* Total Customers
* Average Purchase Amount
* Average Review Rating
* Revenue by Category
* Sales by Category
* Revenue by Age Group
* Subscription Status Analysis
* Customer Segmentation Insights

### 7. Reporting & Presentation

* Created a detailed project report.
* Documented methodology, findings, and recommendations.
* Designed a presentation using Gamma AI for stakeholder communication.

---

## Key Findings

* Male customers generated higher overall revenue than female customers.
* Loyal customers represented the largest customer segment.
* Express shipping customers showed slightly higher average purchase amounts.
* Certain products exhibited strong dependence on discounts.
* Young Adult customers contributed the highest revenue among age groups.
* Non-subscribers generated the majority of total revenue, indicating opportunities for subscription growth.

---

## Business Recommendations

1. Promote exclusive subscriber benefits to increase subscriptions.
2. Implement customer loyalty programs for repeat buyers.
3. Optimize discount strategies to balance revenue and profitability.
4. Focus marketing campaigns on high-performing customer segments.
5. Highlight top-rated and best-selling products in promotions.

---

## Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
│   ├── raw_data.csv
│   └── cleaned_data.csv
│
├── notebooks/
│   └── EDA.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── dashboard/
│   └── PowerBI_Dashboard.pbix
│
├── reports/
│   ├── Project_Report.pdf
│   └── Presentation_Gamma.pdf
│
├── screenshots/
│   └── dashboard.png
│
└── README.md
```

---

## How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/customer-shopping-behavior-analysis.git
```

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2
```

### Run Analysis

```bash
jupyter notebook
```

Open the EDA notebook and execute all cells.

### SQL Analysis

1. Create a PostgreSQL database.
2. Import the cleaned dataset.
3. Execute queries from `analysis_queries.sql`.

### Power BI Dashboard

1. Open `PowerBI_Dashboard.pbix`.
2. Refresh the data source.
3. Explore the interactive dashboard.

<img width="552" height="313" alt="{B4157317-B9B8-4A63-B158-DAF9BD0E1966}" src="https://github.com/user-attachments/assets/18659df9-664e-4acd-82e4-a2894ec364fa" />

---

## Results


This project demonstrates a complete Data Analytics workflow:

✔ Data Loading and Cleaning
✔ Exploratory Data Analysis
✔ Feature Engineering
✔ SQL-Based Business Analysis
✔ Interactive Power BI Dashboard
✔ Business Recommendations
✔ Professional Reporting and Presentation

The project showcases practical skills in Python, SQL, Data Visualization, Business Intelligence, and Data Storytelling.
