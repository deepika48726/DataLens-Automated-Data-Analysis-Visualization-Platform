# DataLens 📊

### Automated Data Analysis & Visualization Platform

DataLens is an interactive automated data analysis platform that transforms raw datasets into meaningful insights through automated exploratory data analysis (EDA).

Users can upload CSV or Excel datasets and instantly receive data quality reports, statistical summaries, and automatically generated visualizations based on the structure and characteristics of the uploaded data.

Built using **Python, Pandas, Plotly, and Gradio**.

---

## ✨ Features

### 📂 Dynamic Dataset Upload

* Upload CSV and Excel datasets directly through the application
* Supports different datasets without modifying the code
* Automatically reads and processes uploaded files

### 🔍 Automated Dataset Exploration

Provides an overview of uploaded datasets:

* Number of rows and columns
* Column names
* Data types
* Dataset structure

### 🧹 Data Quality Analysis

Automatically identifies:

* Missing values
* Duplicate records
* Potential data quality issues
* Column datatype information

### 📈 Statistical Analysis

Generates automatic statistical summaries for numerical features:

* Mean
* Median
* Standard deviation
* Minimum and maximum values

### 📊 Intelligent Visualization Generation

Automatically selects suitable visualizations based on dataset characteristics:

* **Scatter plots** → Relationships between numerical variables
* **Bar charts** → Category-based comparisons
* **Histograms** → Numerical data distributions

The visualization system analyzes column types instead of relying on predefined datasets.

### 🖥️ Interactive Dashboard Interface

* Built with Gradio
* User-friendly upload workflow
* Organized analysis sections
* Interactive Plotly visualizations

---

## 🛠️ Tech Stack

| Technology | Usage                        |
| ---------- | ---------------------------- |
| Python     | Core development             |
| Pandas     | Data processing and analysis |
| Plotly     | Interactive graphs           |
| Gradio     | Web interface                |
| OpenPyXL   | Excel file support           |

---

## 🚀 Workflow

```
Upload Dataset
        ↓
Dataset Processing
        ↓
Data Quality Analysis
        ↓
Statistical Analysis
        ↓
Visualization Recommendation
        ↓
Generated Insights
```

---

## 🔮 Future Enhancements

### 🤖 AI-Powered Insights

* Generate natural language explanations of dataset patterns
* Allow users to ask questions about their data
* Provide automated insight summaries

### 🧹 Automated Data Cleaning

* Handle missing values automatically
* Remove duplicates
* Recommend preprocessing techniques

### 📊 Advanced Visualization Engine

* Improved graph recommendations using:

  * Data distribution
  * Correlation analysis
  * Outlier detection
  * Feature relationships

### 📄 Report Generation

* Export analysis results as:

  * PDF reports
  * HTML dashboards
  * Downloadable summaries

### 📈 Advanced Analytics

* Correlation heatmaps
* Outlier detection
* Trend analysis
* Basic predictive modeling

### 🔮 Upcoming Features
* Support generation of multiple visualization types:
   * Line charts
   * Bar charts
   * Scatter plots
   * Histograms
   * Box plots
   * Heatmaps
   * Pie charts
* Generate multiple graphs together using subplot layouts
* Automatically compare different features and relationships
* Improve graph selection based on dataset characteristics
---
## 👩‍💻 Author

**Deepika**

---

## ⭐ Project Motivation

DataLens was created to simplify exploratory data analysis by reducing the manual effort required to understand and visualize datasets. It aims to make data exploration faster and more accessible for users with different levels of technical expertise.

## ⚠️ Version Disclaimer

DataLens is currently in its **first version (V1)**, developed as a proof of concept to demonstrate the idea of an automated data analysis and visualization platform.

This version focuses on building the core workflow:

* Uploading datasets dynamically
* Performing basic data quality checks
* Generating statistical summaries
* Creating automated visualizations

As this project continues to evolve, more advanced features, improved visualization capabilities, enhanced UI, and smarter analysis methods will be added in future versions.

