# 🛒 Superstore Sales Analysis

An end to end **data analysis project** exploring sales performance, customer behavior, and regional trends for a retail superstore dataset from [Kaggle](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting).  
This project demonstrates **data cleaning, feature engineering, univariate and bivariate analysis**, and concludes with an interactive **Power BI dashboard** for business insights.

---

## 📁 Project Structure

├── 01-Data-Inspection.ipynb # Initial exploration and dataset overview <br>
├── 02-Data-Cleaning.ipynb # Handling missing values and data formatting <br>
├── 03-Feature-Engineering.ipynb # Derived features and business metrics <br>
├── 04-Univariate-Analysis.ipynb # Exploring individual variable distributions <br>
├── 05-Bivariate-Analysis.ipynb # Relationship analysis between variables <br>
│ <br>
└── Superstore-sales-analysis-dash.pbix # Final Power BI Dashboard <br>

---

## 🎯 Objective

The goal of this project is to analyze **sales, profit, and customer trends** to identify:
- Key revenue driving categories and regions  
- Consumer behavior patterns  
- Shipping preferences and seasonal order patterns  
- Outlier impacts on sales distribution  

---

## 🧩 Tools & Technologies

| Category | Tools Used |
|-----------|-------------|
| Programming | Python (Pandas, NumPy, Matplotlib, Seaborn) |
| Visualization | Power BI |
| Environment | Jupyter Notebook |
| Data Source | [Kaggle - Superstore Dataset](https://www.kaggle.com/datasets/rohitsahoo/sales-forecasting) |

---

## 🔍 Exploratory Data Analysis (EDA)

### **Univariate Analysis**
- **Standard Class** is the majority, comprising **59.8%** of all orders.  
- **Consumer Segment** dominates sales with **52.1%** share.  
- **California** leads with **28.2%** of orders, followed by **New York City (20.7%)**.  
- **Office Supplies** is the most ordered category (~60%), mainly **Binders** and **Paper**.  
- **Sales** column shows significant outliers and a strong positive skewness (**12.9%**).  
- **Peak months:** November, December, and September.  
- **Lowest months:** January and February.  
- **Tuesday** records the most orders, while **Thursday** dips to **5.5%**.  

### **Bivariate Analysis**
- **Standard Class** dominates across all customer segments and product categories.  
- **Consumer Segment** leads across every region with **5101 orders**, while **Home Office** in the South has the fewest.  
- **Shipping Preference Order:** Standard > Second > First > Same Day.  
- **Binders** are the top sub category across all customer types; **Copiers** are the least ordered.  
- **Average order value** remains nearly constant across all regions.  
- **West & East regions** dominate in total orders due to higher order volume, not higher average sales.  
- **Office Supplies** generate high total sales via numerous low value transactions, while **Technology** items have fewer but high value sales (some over **$20,000**).  
- **Pattern:** ~4 day gap between order and shipment dates.  
- **Quarter 4 (Oct–Dec)** shows the highest order activity nationwide.  
- **High volatility** in months like **March** and **January**, indicating unpredictable sales trends.  

---

## 📊 Key Insights

✅ **California** and **New York City** are sales hotspots.  
✅ **Consumer Segment** drives over **50%** of total sales.  
✅ **Office Supplies** dominate in order count; **Technology** drives large individual sales.  
✅ **Sales distribution** is right skewed with notable outliers.  
✅ **Tuesday** is the most active sales day.  
✅ **Q4** brings peak business activity.  
✅ **Standard Class** shipping is the clear customer favorite.  
✅ **Consistent order to ship lag**: ~4 days.  
✅ **Sales volatility** is high early in the year and during March.

---

## 📈 Dashboard Preview

📊 The **Power BI dashboard** summarizes regional and segment based sales performance, order trends, and category wise revenue insights.  
It enables quick filtering by:
- Region  
- Category  
- Customer Segment   

<img width="887" height="501" alt="image" src="https://github.com/user-attachments/assets/e6f0eded-c763-4c7a-a9e7-9ed49afd1780" />



*(File: `Superstore-sales-analysis-dash.pbix`)*

---

## 🧠 Learnings

- Data cleaning & feature engineering best practices  
- Visual storytelling through Power BI  
- Statistical interpretation of business trends  
- Identifying actionable insights for decision making  

---


**© 2025 | Superstore Sales Analysis | Data Analytics Project**
