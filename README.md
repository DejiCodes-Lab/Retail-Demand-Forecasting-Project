# 🛒 Retail Sales & Demand Analysis

## 📌 Project Overview
This project analyzes retail sales data to uncover customer purchasing patterns, product performance, and sales trends across time, regions, and customer segments. The goal is to provide **data-driven insights** that can support better inventory planning, sales strategy, and business decision-making.

The project is designed as an **end-to-end data analysis workflow**, using multiple tools commonly used in industry.

---

## 🎯 Business Objectives
- Identify top-performing products and categories by sales and quantity  
- Understand monthly and yearly sales trends  
- Analyze customer segments and regional performance  
- Support inventory and demand planning through historical analysis  

---

## 🗂️ Dataset Description
The dataset consists of **three relational tables**:

### 1. Orders Table
Contains transactional sales data including:
- Order date  
- Product sold  
- Quantity and sales value  
- Region and store type  

### 2. Products Table
Contains product-level information:
- Product name and category  
- Cost price  
- Reorder level  

### 3. Customers Table
Contains customer demographics:
- Customer segment  
- City, state, and country  

> The data spans **two years (2023–2024)** and simulates realistic retail operations.

---

## 🛠️ Tools & Technologies Used
- **Excel** – Data cleaning, validation, and pivot-table analysis  
- **Python** – Exploratory Data Analysis (pandas, matplotlib)  
- **Power BI** – Interactive dashboards and business storytelling  

---

## 🔍 Key Analysis Performed

### 📊 Sales Performance Analysis
- Identified **top 3 products by total sales**  
- Analyzed category-wise and sub-category performance  
- Compared sales trends across regions and store types  

### 📈 Time-Based Trend Analysis
- Monthly and yearly sales trends  
- Seasonal patterns in product demand  
- Growth and decline patterns across categories  

### 👥 Customer & Regional Insights
- Sales contribution by customer segment  
- Regional sales distribution  
- Store type performance (Online vs Physical)  

---

## 📌 Key Insights
- A small number of products contribute a large share of total revenue  
- Certain categories show consistent demand over time, while others are more volatile  
- The consumer segment generates the highest sales volume  
- Regional differences suggest opportunities for targeted marketing and inventory optimization  

---

## 📈 Demand Trend Interpretation (Top Product)

The monthly demand for the top-selling product shows **significant short-term fluctuations**, with noticeable spikes and drops across different months. This indicates that customer purchasing behavior is not constant and may be influenced by factors such as promotions, stock availability, or seasonal buying habits.

To better understand the underlying pattern, a **3-month moving average** was applied. While the actual demand appears highly volatile, the smoothed trend reveals a **relatively stable underlying demand pattern**. A temporary slowdown is visible around the middle of the period, followed by a recovery toward the later months.

Overall, there is **no strong long-term upward or downward trend**, suggesting that demand for this product remains generally stable over time.

### Business Implication
Although raw monthly demand is volatile, the smoothed trend indicates that this product is **suitable for trend-based inventory planning**. Management should avoid reacting to short-term spikes or drops and instead base replenishment decisions on the underlying demand trend to reduce the risk of overstocking or stockouts.

---

## 📊 Power BI Dashboard
The Power BI dashboard includes:
- Sales overview KPIs  
- Monthly sales trends  
- Top products and categories  
- Regional and customer segment analysis  
- Business insights and recommendations  

---

## 🚀 Next Steps (Planned Enhancements)
- Implement **demand forecasting** for top-selling products  
- Compare actual vs predicted demand  
- Introduce machine learning models for customer and product segmentation  
- Add forecast-driven inventory recommendations  


---

## 👤 Author
**Ayodeji**  
Aspiring Data Analyst / Data Scientist  

- **Skills:** Python | SQL | Power BI | Excel  
- **GitHub:** https://github.com/DejiCodes-Lab  
- **LinkedIn:** https://www.linkedin.com/in/abdul-haleem-ayodeji-044a82310  

---
