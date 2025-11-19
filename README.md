# Lark Base & Excel: From Raw Data to Interactive Sale Reports
> This project showcases an end-to-end data analysis workflow, from raw accounting data to an automated, interactive sales dashboard. using Excel and Lark Suite. The project showcases real-world business intelligence skills applicable to e-commerce, retail, and B2B sales environments.
## 🚀 Project Overview
This project builds a unified sales performance dashboard that consolidates data from multiple channels and provides leadership with a full Year-to-date, Month-to-date, Weekly overview of revenue, orders, categories, brands, and product performance.
![alt text](https://github.com/annin317/Lark-Base-Excel-From-Raw-Data-to-Interactive-Sale-Reports/blob/2ebe848f13f396ef3c99e674d36611404dda1e9a/Lark-Base-Excel-From-Raw-Data-to-Interactive-Sale-Reports.png)
The dashboard supports tracking and allows to evaluate performance across all business channels.
## 🎯 Business Problem
The dashboard was created to solve a core business problem:
> Leadership lacked a single source of truth for actual revenue performance across all sales channels and categories.

This project enables:
- A consolidated view of real revenue (from accounting system)
- Easier cross-team evaluation of performance (BOD, Finance, Sales, Marketing, Ops)
- Faster decision-making with accurate, clean, and standardized reporting

## 📂 Dataset Overview
- Data source: Internal accounting system
- Transaction volume: ~100,000+ orders in 2025 (as of Nov 19, 2025)
- Final merged dataset size: 200,000 – 1,000,000 rows
- Data fields (selected): Invoice code, SKU, Selling price, Quantity, VAT, Revenue, Warehouse, Product name, Created date, Invoice date, **Address (raw, unstructured)**, Notes & logs
## 🛠️ Tools & Technologies
### Tools
| Tool | Purpose |
|------|---------|
| **Excel** | Data extraction, cleaning, and initial analysis |
| **Lark Base** | Data organization and table management |
| **Lark Dashboard** | Interactive visualization and reporting |
| **Finance System** | Source system for sales data |
### Techniques
- ETL design
- Data cleaning & transformation
- KPI calculation
- Dashboard design & visualization
- Address normalization using AI model with custom rules
## 🔧 Data Processing Workflow
1. **Data Extraction**
   - Extract sales data from finance system
   - Export to Excel for initial review
2. **Data Cleaning**
   - Remove outliers and anomalies
   - Standardize data formats
   - Validate data integrity
   - Handle missing values
3. **Data Classification**
   - Categorize by region, product, channel
   - Create hierarchical structures
   - Apply business logic rules
4. **Data Loading**
   - Import cleaned data to Lark Base
   - Structure tables with relationships
   - Define data types and constraints
5. **Dashboard Creation**
   - Design KPI metrics
   - Build interactive visualizations
   - Configure filters and drill-downs
   - Test and validate outputs
## 📊 Dashboard Structure
The dashboard includes several analytical layers:
### ✔ Main Overview (YTD)
- Total revenue & orders
- Sales by channel
- Sales by category
- Sales by brand
- Sales by province
- Top 20 products (Sales and transaction)
### ✔ Monthly & Weekly Breakdown
- Trendline revenue
- Category breakdown by time
- Channel comparison
- SKU-level drilldown
### ✔ Channel-Specific Tabs
Each channel group (B2C, B2B2C, B2B, Mall, Online, Offline…) has a dedicated tab with:
- Channel revenue
- Top categories
- Top SKUs
- Weekly performance
  
**Strength: From one single data source (Lark Base), the dashboard supports deep breakdowns without redundant manual work.**
  
## 🔍 Key Insights
A few notable insights identified from the dashboard:
1. B2C contributes ~47% of total revenue, making it the most influential channel.
2. Dairy-related subcategories dominate sales, indicating strong product-market fit.
3. Top 5 SKUs account for a disproportionately high revenue share, implying product dependency risk.
4. Offline B2B2C channels, though smaller, generate stable revenue and should be maintained.
5. Some channels show declining weekly growth, signaling the need for campaign optimization.
## 🧭 Business Recommendations
Based on the insights:
- Strengthen B2C performance, especially high-margin categories.
- Diversify product portfolio to reduce reliance on top SKUs.
- Expand winning subcategories (e.g., Dairy) through marketing & bundling.
- Improve performance in lagging channels through targeted promotions.
- Invest in regional targeting, using cleaned provincial data.
