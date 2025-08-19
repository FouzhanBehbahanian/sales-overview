# Sales Overview Dashboard

## Introduction
This project presents an executive summary of sales performance using a public sample dataset.  
The dashboard was developed in **Power BI** to demonstrate KPI reporting, category analysis, and regional performance insights.  
It reflects the type of dashboards that executives and sales managers rely on for decision-making in retail and e-commerce industries.

---

## Dataset
- **Source**: Public sample e-commerce dataset (non-confidential)  
- **Scope**: Includes product details, orders, sales amounts, list prices, regions, and business types  
- **Purpose**: To simulate a realistic retail business reporting scenario

---

## Objectives
- Provide a high-level overview of sales performance against targets  
- Identify which product categories generate the most revenue  
- Compare sales performance by region and business type  
- Support management in tracking progress and planning growth strategies

---

## Dashboard Features and Graph Analysis

### 1. KPI Cards
- **Products**: 295 unique products  
- **Orders**: 31.46K total orders  
- **Sales Amount**: $80.45M  
- These KPIs immediately set the stage, providing an executive with a **snapshot of business scale**.

### 2. Gauge Chart – Sales Performance vs Target
- **Target**: $160.9M  
- **Current Sales**: $80.45M  
- The gauge shows that the company is at **50% of its sales target**.  
- Business implication: At this pace, either the target will not be met, or stronger performance is needed in upcoming quarters.

### 3. Bar Chart – Category vs List Price
- Shows revenue contribution of each product category.  
- **Bikes** dominate with the highest revenue share.  
- **Components** contribute moderately.  
- **Clothing and Accessories** underperform, signaling an area for strategic growth.  
- Business implication: Decision-makers may consider promotions, cross-selling, or new product development in weaker categories.

### 4. Pie Chart – Market Share by Category
- Confirms dominance of **Bikes (64%)** in total revenue.  
- Helps visualize the imbalance in category sales.  
- Business implication: High reliance on a single category can be risky if market demand shifts.

### 5. Table – Sales by Country and Business Type
- Provides detailed breakdown by **region (United States, Canada, Australia, etc.)** and **business type (Value Added Resellers, Warehouses, Specialty Bike Shops)**.  
- Insight: U.S. and Canada drive the majority of revenue, primarily through **Value Added Resellers**.  
- Business implication: Heavy reliance on a few regions or business types may limit global growth opportunities.

---

## Results
- Current sales are at **50% of the annual target** ($80.45M out of $160.9M).  
- **Bikes** generate the majority of revenue, but the company lacks diversification across product categories.  
- **Clothing and Accessories** remain underperforming, creating potential growth opportunities.  
- **U.S. and Canada** dominate sales, raising questions about geographic expansion strategies.  

---

## Real-World Application
This type of dashboard is directly applicable in industries such as:  
- **Retail & E-commerce**: Tracking sales trends across categories and channels  
- **Wholesale & Distribution**: Monitoring orders by resellers and warehouses  
- **Consumer Goods**: Identifying category strengths and weaknesses for inventory planning  

**Example Business Problem Solved:**  
An e-commerce retailer facing stagnating sales could use this dashboard to:  
- Benchmark current sales against targets  
- Identify over-reliance on a single product line (e.g., Bikes)  
- Highlight weak-performing categories (e.g., Clothing) for promotional campaigns  
- Analyze regional performance to inform expansion into new markets  

By providing executives with a **clear, real-time view of sales KPIs**, this dashboard supports both **strategic planning** and **operational decision-making**.

---
## File strucure
/sales-overview
   ├── sales_overview.png    # Dashboard screenshot
   ├── sales_overview.pbix   # Power BI file
   ├── dataset.csv           # Sample dataset 
   ├── queries.M-query       # SQL queries used in data prep
   └── README.md             # Project documentation
   
## Preview
[Sales Overview]<img width="2347" height="1104" alt="image" src="https://github.com/user-attachments/assets/bb694b26-a640-4fa1-a240-acd84ad85d0f" />
