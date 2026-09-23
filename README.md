# 🌾 Agricultural Crop Yield Analysis

An interactive **Agricultural Crop Yield Analysis Dashboard** built using **Microsoft Excel** to analyze crop productivity, production patterns, irrigation, fertilizer usage, soil conditions, seasonal trends, and rainfall impact across different regions.

---

## 📌 Project Overview

Agriculture plays an important role in the Indian economy, and crop productivity can vary significantly depending on factors such as **state, crop, season, irrigation, fertilizer usage, soil type, rainfall, and temperature**.

This project uses Microsoft Excel to transform agricultural data into meaningful insights through:

* Data cleaning and preparation
* PivotTables
* PivotCharts
* KPI cards
* Interactive slicers
* Statistical visualizations
* Scatter plot analysis
* Box plot analysis
* Interactive dashboard

The final output is an **interactive Agricultural Crop Yield Analysis Dashboard** that helps users explore crop performance and identify important agricultural patterns.

---

## 🎯 Objectives

The main objectives of this project are:

* Analyze crop yield across different states and regions.
* Compare productivity between different crops.
* Understand seasonal production patterns.
* Analyze the relationship between irrigation and crop yield.
* Study fertilizer usage and its relationship with yield.
* Compare yield across different soil types.
* Analyze rainfall and its relationship with crop yield.
* Identify variations in crop productivity.
* Provide an interactive dashboard for agricultural monitoring.
* Present agricultural data in a clear and easy-to-understand format.

---

## 🗂️ Dataset

The project is based on agricultural crop data containing information related to crop production and environmental/resource factors.

### Major Data Fields

| Column              | Description                                   |
| ------------------- | --------------------------------------------- |
| Crop ID / Record ID | Unique identifier for the agricultural record |
| State               | State where the crop was cultivated           |
| District            | District where the crop was cultivated        |
| Year                | Year of cultivation                           |
| Season              | Agricultural season                           |
| Crop Name / Crop    | Name of the crop                              |
| Area                | Cultivated agricultural area                  |
| Production          | Total crop production                         |
| Yield               | Crop productivity                             |
| Irrigation Type     | Type/method of irrigation                     |
| Fertilizer Used     | Fertilizer information                        |
| Rainfall            | Rainfall received                             |
| Soil Type           | Type of soil                                  |
| Temperature         | Temperature during cultivation                |

> **Note:** The exact available columns depend on the dataset version used for the project.

---

# 🧹 Data Cleaning & Preparation

Before performing analysis, the agricultural dataset was prepared for analysis.

### Data preparation activities included:

* Checking for duplicate records
* Checking missing values
* Standardizing text values
* Removing unnecessary spaces
* Checking consistency in crop names
* Checking state and district names
* Checking numerical fields
* Verifying yield-related calculations
* Preparing data for PivotTable analysis

### Excel functions/features used

* `TRIM()`
* `PROPER()`
* Filtering
* Sorting
* Remove Duplicates
* Conditional Formatting
* PivotTables
* PivotCharts

---

# 🔄 Data Analysis

The project analyzes agricultural data from multiple perspectives.

## 1. Crop-wise Yield Analysis

Crop-wise analysis is used to compare the average yield of different crops.

**Visualization:**

* Crop-wise Average Yield Chart

This helps identify differences in productivity among crops.

---

## 2. Year-wise Yield Analysis

Year-wise analysis is used to understand how crop yield changes across different years.

**Visualization:**

* Year-wise Average Yield Chart

This helps identify changes and trends in agricultural productivity over time.

---

## 3. Season-wise Production Analysis

Agricultural production can vary depending on the season.

**Visualization:**

* Season-wise Production Chart

This helps compare total production across different agricultural seasons.

---

## 4. Irrigation-wise Yield Analysis

Irrigation is an important factor affecting agricultural productivity.

**Visualization:**

* Irrigation-wise Yield Chart

This analysis helps compare crop yield across different irrigation methods.

---

## 5. Fertilizer-wise Yield Analysis

Fertilizer usage can have an impact on crop productivity.

**Visualization:**

* Fertilizer-wise Yield Chart

This helps analyze yield differences associated with fertilizer usage.

---

## 6. Soil-wise Yield Analysis

Different crops perform differently depending on soil conditions.

**Visualization:**

* Soil-wise Yield Chart

This analysis compares crop yield across different soil types.

---

## 7. State-wise Yield Analysis

Agricultural productivity can vary significantly between states.

**Visualization:**

* State-wise Average Yield Chart

This helps identify regional differences in crop productivity.

---

# 📊 Dashboard

The project includes an interactive **Agricultural Crop Yield Analysis Dashboard**.

### Dashboard Components

The dashboard contains:

* KPI Cards
* Crop-wise analysis
* Year-wise analysis
* Season-wise production
* Irrigation-wise analysis
* Fertilizer-wise analysis
* Soil-wise analysis
* State-wise analysis
* Rainfall vs Yield analysis
* Box Plot analysis
* Interactive slicers

---

# 📈 KPI Analysis

The dashboard includes important agricultural Key Performance Indicators (KPIs).

### Main KPIs

* **Total Yield**
* **Average Yield**
* **Total Area Cultivated**
* **Average Rainfall**
* Other relevant agricultural metrics available in the dataset

These KPIs provide a quick overview of the overall agricultural performance.

---

# 🌧️ Rainfall vs Yield Analysis

A **Scatter Plot** is used to analyze the relationship between rainfall and crop yield.

### Objective

To understand whether changes in rainfall are associated with changes in crop productivity.

**Chart Type:**

* Scatter Plot

**X-Axis:**

* Rainfall

**Y-Axis:**

* Yield

---

# 📦 Yield Distribution Analysis

A **Box Plot** is used to understand the distribution and variation of crop yield.

It can help identify:

* Median yield
* Spread of yield values
* Variability
* Potential outliers
* Overall yield distribution

---

# 🎛️ Interactive Slicers

The dashboard contains interactive slicers that allow users to filter the analysis dynamically.

### Available Slicers

* **State**
* **Crop Name**
* **Year**
* **Season**

Users can select a specific state, crop, year, or season and analyze the corresponding dashboard results.

The slicers are connected to the relevant PivotTables/PivotCharts so that the dashboard updates interactively.

---

# 🛠️ Tools & Technologies

| Tool                   | Purpose                              |
| ---------------------- | ------------------------------------ |
| Microsoft Excel        | Data analysis and dashboard creation |
| Excel PivotTables      | Data summarization                   |
| PivotCharts            | Data visualization                   |
| Excel Slicers          | Interactive filtering                |
| Excel Formulas         | Data transformation and calculations |
| Conditional Formatting | Data visualization and highlighting  |

---

# 📋 Project Workflow

```text
Raw Agricultural Data
        ↓
Data Cleaning
        ↓
Data Transformation
        ↓
PivotTables
        ↓
PivotCharts
        ↓
KPI Creation
        ↓
Slicers
        ↓
Interactive Dashboard
        ↓
Agricultural Insights
```

---

# 💡 Key Insights

The dashboard can be used to identify:

* Differences in crop productivity across states.
* Crops with relatively higher or lower average yield.
* Changes in agricultural yield across years.
* Seasonal production patterns.
* Differences in yield across irrigation methods.
* Differences in yield associated with fertilizer usage.
* Yield variation across soil types.
* Regional differences in agricultural productivity.
* The relationship between rainfall and yield.
* Distribution and variability of crop yield.

> Specific numerical insights should be added based on the final dataset values.

---

# 📁 Project Structure

```text
Agricultural-Crop-Yield-Analysis/
│
├── Agricultural_Crop_Yield_Analysis.xlsx
│
├── README.md
│
└── screenshots/
    │
    └── dashboard.png
```

---

# 📸 Dashboard Preview

Add your dashboard screenshot here:

```markdown
![Agricultural Crop Yield Analysis Dashboard](screenshots/dashboard.png)
```

---

# 🚀 How to Use the Project

1. Download the Excel workbook.
2. Open `Agricultural_Crop_Yield_Analysis.xlsx`.
3. Navigate to the Dashboard sheet.
4. Use the available slicers.
5. Select different:

   * States
   * Crops
   * Years
   * Seasons
6. Observe how the charts and KPIs change.
7. Use the dashboard to explore agricultural productivity patterns.

---

# 📚 Skills Demonstrated

This project demonstrates practical knowledge of:

* Microsoft Excel
* Data Cleaning
* Data Transformation
* Data Analysis
* PivotTables
* PivotCharts
* Dashboard Development
* KPI Creation
* Data Visualization
* Slicers
* Conditional Formatting
* Statistical Analysis
* Business/Domain Analysis
* Insight Generation

---

# 👨‍💻 Author

**Lalit Patil**

B.Tech – Electronics & Communication Engineering

Interested in:

* Data Analysis
* Python
* SQL
* Microsoft Excel
* Power BI
* Data Visualization

---

# ⭐ Project Highlights

✅ Agricultural data analysis using Excel
✅ Interactive Excel dashboard
✅ KPI cards
✅ PivotTables and PivotCharts
✅ Interactive slicers
✅ Crop-wise analysis
✅ State-wise analysis
✅ Season-wise analysis
✅ Irrigation analysis
✅ Fertilizer analysis
✅ Soil analysis
✅ Rainfall vs Yield scatter plot
✅ Yield distribution using Box Plot
✅ Clean and interactive visualization

---

## 📌 Conclusion

The **Agricultural Crop Yield Analysis** project demonstrates how Microsoft Excel can be used to convert agricultural data into meaningful and interactive visual insights.

The dashboard provides a consolidated view of crop productivity, regional differences, seasonal production, resource usage, soil conditions, and rainfall-related patterns, making the analysis easier to understand and explore.

---

## 🔗 Project Repository

The complete project, including the Excel workbook and dashboard screenshot, is available in this GitHub repository.

**GitHub Repository:**
`https://github.com/<your-username>/Agricultural-Crop-Yield-Analysis`

---
