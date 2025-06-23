# powerbi_project_website_performance_analytics
Built a Power BI dashboard to analyze website performance using metrics like page views, session duration, bounce rate, and conversion rate. Created interactive visuals including KPIs, charts, and maps. Filtered top 100 visitors to uncover insights on engagement and conversions.
# 📊 Website Performance Dashboard - Power BI Project

This project involves building an interactive Power BI dashboard to analyze website performance metrics such as user behavior, engagement, and conversion efficiency.

## 📁 Dataset
- **File:** `website_performance_analytics.xlsx`
- **Source:** Provided in the course resources
- The dataset includes metrics like page views, session duration, bounce rate, conversion rate, traffic source, visitor type, and location.

## 📌 Objective
To create a comprehensive and visually insightful dashboard in Power BI that tracks and analyzes user behavior and conversion performance across various metrics and dimensions.

---

## ✅ Tasks Performed

### 🔹 Data Preparation
- Loaded the `website_performance_analytics.csv` dataset into Power BI.
- Converted:
  - `Bounce_Rate` and `Conversion_Rate` into **percentage format**.
  - Reduced decimal places to **zero**.
- Set the **data category** for `Location` to **City**.

### 🔹 Dashboard Configuration
- Added a report title: **"Website Performance Dashboard"**.
- Used `Exit_Page` as a **slicer filter** in the title bar.

### 🔹 KPI Cards
Created KPI summary cards showing **average values** for:
- `Page_Views`
- `Session_Duration`
- `Bounce_Rate`
- `Conversion_Rate`

### 🔹 Visualizations
- 📈 **Donut Charts**:
  - Average `Bounce_Rate` by `Visitor_Type`
  - Average `Conversion_Rate` by `Visitor_Type`
- 📊 **Bar Chart**:
  - Average `Conversion_Rate` by `Traffic_Source`
- 🗺️ **Map Chart**:
  - Average `Conversion_Rate` by `Location` (City-level granularity)
- 🧾 **Table Visual**:
  - Columns: `Visitor_ID`, `Page_Views`, `Session_Duration`, `Conversion_Rate`
  - Aggregated using average values (excluding `Visitor_ID`)
  - Sorted by `Conversion_Rate` in descending order
  - Included **cell elements** for all columns except `Visitor_ID`
  - Applied a **Top N filter** to show only the **Top 100 visitors by average Conversion Rate**

---

## 💡 Insights Gained
- Identification of which traffic sources drive higher conversion rates.
- Comparison of new vs. returning visitor behavior.
- Performance distribution across various cities.
- Behavior patterns of the top converting visitors.

---

## 🛠 Tools Used
- **Power BI Desktop**
- **Data modeling and visualization**
- **DAX (Data Analysis Expressions) for summarization**

---

## 📷 Preview
><img width="614" alt="image" src="https://github.com/user-attachments/assets/e7ba806e-0c84-46a8-be4b-8790421de250" />
---

## 🧩 File Info
- `website_performance_dashboard.pbit`: Power BI Template file
- `website_performance_analytics.xls`: Original dataset

---

## 🚀 How to Use
1. Download the `.pbit` file and open it in Power BI Desktop.
2. Load the dataset when prompted.
3. Interact with the dashboard filters to explore insights.

---

## 📬 Contact
Feel free to connect with me on [www.linkedin.com/in/rani-v-293251219] if you have any questions or suggestions.

---
