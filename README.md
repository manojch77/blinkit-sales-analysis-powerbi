## 📊 Project Overview

The **Blinkit Grocery Sales & Performance Analytics Dashboard** is an interactive Business Intelligence project developed using **Microsoft Power BI**.

The objective of this project is to analyze grocery sales performance across different outlet types, outlet sizes, outlet locations, product categories, item fat content, and outlet establishment years.

The dashboard transforms raw grocery sales data into an interactive analytical report that can be used to understand business performance and compare different outlet and product segments.

---

## 🎯 Business Objective

The project focuses on answering important business questions such as:

* What is the overall sales performance?
* What is the average sales value?
* How many items are being sold?
* What is the average customer rating?
* Which outlet types generate higher sales?
* How does outlet size affect sales?
* How does sales performance vary by outlet location?
* Which product categories contribute to sales?
* How does fat content affect sales distribution?
* How have sales changed based on outlet establishment year?
* How do different outlet types compare across key KPIs?

---

## 🛠️ Tools & Technologies

| Technology            | Purpose                                   |
| --------------------- | ----------------------------------------- |
| Microsoft Power BI    | Dashboard development and visualization   |
| Power Query           | Data transformation and preparation       |
| DAX                   | KPI and analytical measure creation       |
| Data Modeling         | Organizing analytical data                |
| Microsoft Excel / CSV | Dataset handling                          |
| GitHub                | Project version control and documentation |

---

## 📂 Dataset

The project uses grocery sales data containing information related to products and retail outlets.

### Major Data Attributes

The analysis includes fields such as:

* Item Type
* Item Fat Content
* Item Visibility
* Item Weight
* Sales
* Outlet Type
* Outlet Size
* Outlet Location Type
* Outlet Establishment Year
* Customer Rating

These attributes are used to analyze product-level and outlet-level sales performance.

---

## 📈 Key KPIs

The dashboard includes the following major KPIs:

### Total Sales

Measures the overall sales generated across the analyzed grocery outlets.

### Average Sales

Measures the average sales performance of the products/outlets.

### Number of Items

Represents the number of items included in the analysis.

### Average Rating

Represents the average customer rating associated with the analyzed products/outlets.

---

## 📊 Dashboard Components

The Power BI dashboard contains multiple interactive visualizations.

### 1. KPI Cards

The dashboard provides a high-level summary using:

* Total Sales
* Average Sales
* Number of Items
* Average Rating

These KPIs allow users to quickly understand overall business performance.

---

### 2. Fat Content Analysis

A donut chart analyzes sales distribution based on:

* Low Fat
* Regular

This helps understand how sales are distributed between different product fat-content segments.

---

### 3. Outlet Location Analysis

Sales are analyzed across different outlet location types.

This allows comparison of sales performance across different location segments.

---

### 4. Item Type Analysis

A bar chart compares sales across different grocery product categories.

This helps identify product categories contributing to overall sales.

---

### 5. Outlet Establishment Trend

A line chart analyzes sales across outlet establishment years.

This provides a historical view of sales performance and allows users to observe changes over time.

---

### 6. Outlet Size Analysis

Sales are analyzed across different outlet size categories.

This helps compare performance between:

* Small outlets
* Medium outlets
* Large outlets

---

### 7. Outlet Type Analysis

The dashboard compares different outlet types using multiple metrics.

The analysis includes:

* Total Sales
* Number of Items
* Average Sales
* Average Rating
* Item Visibility

This provides a more detailed comparison of outlet performance.

---

### 8. Interactive Filters

The dashboard includes interactive filters/slicers for:

* Outlet Location Type
* Outlet Size
* Item Type
* Performance Metrics

Users can apply these filters to dynamically change the dashboard analysis.

---

## 🧮 DAX & Measures

The dashboard uses analytical measures to calculate important business KPIs.

Examples of analytical measures include:

```DAX
Total Sales =
SUM('BlinkIT Grocery Data'[Sales])
```

```DAX
Average Sales =
AVERAGE('BlinkIT Grocery Data'[Sales])
```

```DAX
Number of Items =
COUNTROWS('BlinkIT Grocery Data')
```

```DAX
Average Rating =
AVERAGE('BlinkIT Grocery Data'[Rating])
```

> Note: The exact DAX implementation may vary depending on the final Power BI data model.

---

## 🔄 Data Analysis Workflow

The project follows a typical Business Intelligence workflow:

```text
Raw Dataset
     ↓
Data Understanding
     ↓
Data Cleaning
     ↓
Data Transformation
     ↓
Data Modeling
     ↓
DAX Measures
     ↓
Data Visualization
     ↓
Interactive Dashboard
     ↓
Business Insights
```

---

## 🔍 Analysis Performed

### Product Analysis

Analyzed sales performance across different item categories and product characteristics.

### Outlet Analysis

Compared sales and KPIs across different outlet types and outlet sizes.

### Location Analysis

Compared sales performance across outlet location categories.

### Time-Based Analysis

Analyzed sales trends according to outlet establishment year.

### Customer Rating Analysis

Used average rating as one of the performance indicators.

### Visibility Analysis

Included item visibility as an analytical metric in outlet-level comparison.

---

## 💡 Business Insights

The dashboard is designed to help stakeholders identify:

* Differences in sales performance between outlet types.
* Sales distribution across product categories.
* Relationship between outlet size and sales performance.
* Differences in sales across outlet location categories.
* Sales distribution between different item fat-content segments.
* Historical sales patterns based on outlet establishment year.
* Outlet-level differences in sales, item count, rating, and visibility.

> The exact numerical findings should be documented after selecting the relevant filters in the final dashboard.

---

## 📸 Dashboard Preview

Add your dashboard screenshot here:

```markdown
![Blinkit Dashboard](Screenshots/dashboard-overview.png)
```

You can also add additional screenshots:

```markdown
![Sales Analysis](Screenshots/sales-analysis.png)

![Outlet Analysis](Screenshots/outlet-analysis.png)
```

---

## 🚀 How to Use the Project

### Step 1 — Install Power BI Desktop

Download and install Microsoft Power BI Desktop.

### Step 2 — Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/blinkit-sales-analysis-powerbi.git
```

### Step 3 — Open the Power BI File

Navigate to:

```text
PowerBI/
```

Open:

```text
Blinkit_Dashboard.pbix
```

### Step 4 — Explore the Dashboard

Use the available slicers and interactive visualizations to analyze:

* Sales
* Products
* Outlet types
* Outlet sizes
* Outlet locations
* Establishment year
* Ratings

---

## 🎓 Skills Demonstrated

This project demonstrates practical knowledge of:

* Power BI
* DAX
* Power Query
* Data Cleaning
* Data Transformation
* Data Modeling
* KPI Development
* Data Visualization
* Exploratory Data Analysis
* Business Intelligence
* Interactive Dashboard Development
* Business Reporting

---

## 📌 Future Improvements

Possible improvements include:

* Adding additional time-based analysis.
* Adding geographic visualization.
* Creating additional calculated measures.
* Adding year-over-year growth metrics.
* Adding advanced DAX calculations.
* Adding automated data refresh.
* Adding more detailed product-level analysis.
* Creating a dedicated executive summary page.

---

### Profiles

* LinkedIn: https://www.linkedin.com/in/manoj229

---

## ⭐ If you found this project useful

Feel free to explore the repository and use the dashboard structure as a reference for Power BI and Business Intelligence projects.
