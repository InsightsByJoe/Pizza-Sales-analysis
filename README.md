# 🍕 Pizza Sales Analysis  

## 📊 Project Overview  
The "Pizza Sales Analysis" project provides an in-depth exploration of pizza sales data to uncover key business insights and trends. Utilizing MySQL Workbench for data extraction and Excel for data visualization, this project examines customer behavior, peak sales periods, best-selling pizzas, and revenue drivers. The dashboard helps stakeholders make informed decisions to enhance sales strategies and operational efficiency.  


![Screenshot 2025-02-20 073653](https://github.com/user-attachments/assets/f47797b2-a3c2-4777-a351-97c9ac35d032)



## 🔗 Data Source  
The dataset for this analysis can be accessed from the following link: [Pizza Sales Dataset](https://drive.google.com/drive/folders/1ecpBALfFUMSK-GOnk-X4nZhC_uK18zih)  

## 🛠 Tools Used  
1. **Excel** - For data cleaning, analysis, and creating interactive dashboards.  
   - Download Excel: [Download Here](https://www.microsoft.com/en-us/microsoft-365/excel)  
2. **MySQL Workbench** - For data extraction and querying.  
   - Download MySQL Workbench: [Download Here](https://www.mysql.com/products/workbench/)  

## 📥 Data Loading and Inspection  
1. Data was imported into MySQL Workbench using the Import Wizard.  
2. Preliminary inspection was conducted to understand the schema, data types, and structure.  
3. Checked for missing values, duplicates, and inconsistencies.  

## 🧹 Data Cleaning  
1. Removed duplicate records to ensure data integrity.  
2. Handled missing values by either imputing them or omitting the affected rows.  
3. Reformatted date columns and extracted day, month, and year for trend analysis.  
4. Separated date and time fields using **Excel's Text to Columns** feature, converting time into a more readable format.  
5. Used **TEXT() function** in Excel to extract the day from the date for weekday analysis.  

## 📊 Data Analysis & Visualization  
1. **Sales Trends by Day and Hour**: Identified peak sales days (Friday & Saturday) and peak hours (12-1 PM and 5-8 PM).  
2. **Category & Size Analysis**: Classic pizzas and large sizes were the top performers.  
3. **Best & Worst Sellers**: Classic Deluxe and Chicken Pizzas were the highest revenue generators, while the Brie Pizza performed the worst.  
4. **Revenue and Order Metrics**: Analyzed total revenue ($817,860), total orders (21,350), and average order value ($38.31).  

## 🔍 Excel Functions Used  
1. **TEXT TO COLUMNS**: To separate date and time fields, making time analysis more efficient.  
2. **COUNTIFS**: For calculating frequency distributions (e.g., orders per day).  
3. **TEXT()**: To extract day names from date fields for weekday trend analysis.  

## 📈 Analysis Results  
- **Peak Sales Periods**: Evenings (5-8 PM) on weekends are the busiest times, suggesting targeted promotions during these hours.  
- **Top Performers**: Classic Deluxe and Chicken Pizzas are the highest revenue generators.  
- **Low Performers**: The Brie Pizza consistently underperforms, indicating a potential need for discontinuation or recipe revamp.  
- **Size Preferences**: Large pizzas dominate sales, contributing most to total revenue.  

## 📌 Recommendations  
1. **Promotional Strategies**: Implement targeted promotions during peak hours (5-8 PM) and on weekends to maximize revenue.  
2. **Menu Optimization**: Review and possibly revamp or discontinue low-performing items like the Brie Pizza.  
3. **Inventory Management**: Align inventory stocking with peak demand times to minimize waste and maximize sales.  

## ⚠️ Limitations  
1. The analysis does not consider external factors such as holidays, weather, or local events, which could impact sales.  
2. The dataset lacks customer demographic information, limiting customer segmentation analysis.  
3. Only historical data is analyzed; predictive analytics could further enhance decision-making.  

## 📝 Conclusion  
The Pizza Sales Analysis provides actionable insights into customer preferences and sales patterns. By leveraging these insights, the business can optimize inventory, adjust marketing strategies, and enhance overall profitability.  

## 📚 Reference  
- [Excel Support](https://support.microsoft.com/excel)  
- [Pizza Sales Dataset](https://drive.google.com/drive/folders/1ecpBALfFUMSK-GOnk-X4nZhC_uK18zih)  

--- 
