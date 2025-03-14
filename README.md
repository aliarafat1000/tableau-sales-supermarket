# 📊 Sales and Customer Dashboard Project

### 🚀 Project Overview
This project showcases advanced time series analysis for year-over-year (YoY), month-over-month (MoM), and week-over-week (WoW) sales trends. 

[LINK]https://public.tableau.com/views/project_course/SalesDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

---

Sales Dashboard
![Screenshot 2025-03-14 094053](https://github.com/user-attachments/assets/10e95b67-bc89-4803-a1c8-d6522bfee798)

Customer Dashboard
![Screenshot 2025-03-14 090747](https://github.com/user-attachments/assets/fd815fea-c42c-4b20-b147-e6ceb5f0be74)

---

### 🛠️ Skills and Tools Used
| Skill/Tool        | Description                                      |
|------------------|--------------------------------------------------|
| Tableau          | Data visualization and dashboard creation         |
| Data Modeling    | Creating joins and relationships                  |
| EDA (Exploratory Data Analysis) | Analyzing trends and patterns           |
| Time Series Analysis | YoY, MoM, WoW sales analysis                    |
| Data Cleaning    | Handling missing values and data formatting       |
| Calculated Fields| Custom formulas for advanced insights             |
| Filters and Parameters | Interactive dashboards for deeper analysis |
| Python           | Data preprocessing and manipulation               |

---

It breaks down data by categories and subcategories to provide deep insights into sales and profitability. Additionally, it features a dedicated dashboard to analyze customer behavior.

Using Tableau's powerful features such as filters, parameters, and calculated fields, I have created dynamic and interactive visualizations that make data exploration intuitive and insightful. The project also includes data modeling with joins and relationships to structure the data efficiently.

---

### 💡 Project Description
The project contains two main dashboards:
1. **Sales Dashboard**: Analyzes sales, profits, and quantities over time. Highlights include:
   - 📈 Total Sales, Total Profits, and Total Quantity with percentage changes compared to the previous year.
   - 🔥 Visualization of highest and lowest months for quick comparison.
   - 📊 Sales and Profit by Category with clear profit/loss distinction.
   - 📅 Sales & Profits Trends over Time, identifying months with above and below average performance.

2. **Customer Dashboard**: Provides insights into customer behavior and profitability, including:
   - 👥 Total Customers, Total Orders, and Average Sales per Customer.
   - 📅 Customer Distribution by Number of Orders for identifying purchasing patterns.
   - 🏆 Top 10 Customers by Profit with detailed breakdowns.

### ✨ Highlights
- Dynamic interactivity for real-time insights.
- Sleek and modern visual design, making insights easily digestible.
- Comprehensive trend analysis to spot growth opportunities.

## 🔍 Interactive Features and Filters

One of the standout features of this dashboard is its **interactivity**. The dashboard is designed to provide an intuitive and engaging user experience, allowing users to explore data seamlessly. Here’s what makes it interactive:

### 📊 Filter Options
- **Category and Subcategory Filters:** Easily filter the data by product categories and subcategories to analyze specific segments of sales and customer behavior.
- **Year Filters:** Choose specific years to compare performance across different time periods.
- **Location Filters:** Analyze data from different regions to understand geographical trends.

![salary-dashboard-filters](https://github.com/user-attachments/assets/673cc8d1-5310-4ba6-98e6-4f724a9b28e9)

### ✨ Interactive Charts
The charts are highly interactive, allowing you to **click on data points** or **select data within one chart** to automatically update all related charts on the dashboard. This interconnected approach ensures that users can quickly drill down into insights without losing context.

These interactive features not only enhance usability but also empower users to make **data-driven decisions** more efficiently!

![salary-chart-filters](https://github.com/user-attachments/assets/4006358a-a344-48fb-95a6-c9af099e0ea1)

---

## 🗃️ Data Model

The data model follows a **star schema** with the **Orders** table as the central fact table, connected to three dimension tables. All data is sourced from **CSV files**, loaded and processed in Tableau for analysis and visualization.  

### 🔗 Data Model Structure:
- **Orders (Fact Table):** Contains transactional data such as order ID, date, sales amount, profit, and quantity.  
- **Customers (Dimension Table):** Stores customer-related information like customer ID, name, and contact details.  
- **Location (Dimension Table):** Holds location-specific data such as city, state, region, or country.  
- **Products (Dimension Table):** Includes product details like product ID, name, category, subcategory, and pricing.  

This data model enables efficient querying and insightful analysis by leveraging joins between the **Orders** fact table and the related dimension tables. The star schema structure is optimized for interactive dashboarding and visualization in Tableau. 💡

![Screenshot 2025-03-14 101812](https://github.com/user-attachments/assets/c3865dfe-df55-4c6d-b038-69e6ce326c6a)

---

### 📂 How to Use
1. Clone the repository.
2. Open the Tableau workbook in Tableau Desktop.
3. Interact with the filters and explore insights across various dimensions.

---

### 🎯 Impact
This project demonstrates my ability to effectively analyze and visualize complex datasets using Tableau. The dashboards offer valuable business insights that drive strategic decision-making and are tailored for real-world applications.

Feel free to reach out if you have any questions or feedback! 😄

