# Bike-Sales-Dashboard
Built an interactive Power BI dashboard to explore bike sales data by age, income, commute distance, and other customer factors.
# 🚴‍♀️ Bike Sales Dashboard | Power BI & MySQL

This project showcases a complete data analytics workflow — from raw data cleaning in **MySQL** to interactive data visualization in **Power BI**. The dashboard explores customer purchasing behavior in a bike sales dataset across various demographic and lifestyle factors.

---

## 📊 Project Highlights

- Visual breakdown of bike purchases by:
  - 👤 Age group
  - 💰 Income level
  - 🚻 Gender
  - 💍 Marital status
  - 🎓 Education
  - 🌍 Region
  - 🚗 Commute distance
- Insightful charts and filters for deep analysis
- Cleaned, transformed, and enriched dataset using MySQL before importing into Power BI

---

## 🧹 Data Cleaning with MySQL

Before building the dashboard, the dataset was cleaned using **SQL queries in MySQL** to ensure accuracy and consistency. Steps included:

- ✅ Creating backup tables to preserve raw data
- 🔄 Removing duplicate rows using `ROW_NUMBER()` and partitioning by ID
- 🧼 Standardizing categorical data (e.g., `'M'` → `'Male'`, `'S'` → `'Single'`)
- 🧮 Creating new features like `age_range` (Young Adults, Middle-Aged, Old Adults)
- 💵 Converting income from string to integer by removing symbols and formatting
- 📊 Calculating averages and purchase counts grouped by demographic segments

The cleaned dataset was then imported into Power BI for visual exploration.

---

## 🛠️ Tools Used

- **MySQL** – For data cleaning and transformation  
- **Power BI Desktop** – For interactive visualization  
- **Power Query** – For additional data shaping  
- **DAX** – For calculated measures and KPIs
