# End-to-End Customer Purchase Behavior Analytics Using Python, MySQL & Power BI

This project builds a complete analytics pipeline for exploring customer purchase behavior. The data was cleaned in Python, stored and queried in MySQL, and visualized through an interactive Power BI dashboard. The goal was to take the dataset from raw CSV to insight-ready visuals using multiple tools working together.

---

## 🛠 Project Workflow

### **1. Data Preparation (Python)**
- Loaded the raw CSV dataset into JupyterLab
- Examined the structure, column types, and missing values
- Cleaned inconsistencies in dates, numerical fields, and categories
- Created new calculated attributes such as `Total Sales`
- Exported a cleaned dataset for database storage

### **2. Database & Querying (MySQL Workbench)**
- Imported the cleaned dataset into MySQL
- Wrote analytical SQL queries to study:
  - Purchase patterns over time
  - Sales contributions by category
  - Payment method usage
  - Discount behavior
- Used query outputs as the basis for dashboard visuals

### **3. Dashboard & Visual Exploration (Power BI)**
- Connected Power BI directly to MySQL tables
- Designed visuals and KPIs for interactive exploration
- Added filters for categories, payment types, and dates
- Built a multi-visual dashboard for exploring the dataset

### **4. Documentation & Presentation**
- Compiled the workflow, visuals, and findings into a structured report
- Created a slide deck explaining how the project was built end-to-end

---

## 🧱 Tooling Decisions

- **Python** for cleaning because it made data formatting and transformation easier
- **MySQL** for analytics because SQL was better suited for grouping and aggregations
- **Power BI** for visualization because it supports direct connection to databases

Together these tools replicated a realistic analytics setup rather than doing everything in a single tool.

---

## 📦 Project Deliverables

This repository includes:

- `.csv` dataset (raw)
- `.ipynb` notebook (cleaning and preprocessing)
- `.sql` file (analytical queries)
- `.pbix` dashboard file
- `.pdf` project report
- `.pptx` presentation slides

---

## 👤 Author

**Kavya Balaji Singh**
