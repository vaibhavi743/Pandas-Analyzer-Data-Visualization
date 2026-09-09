# 📊 Project 9 — Data Analysis & Visualization Program

> A Python-based menu-driven application for data manipulation, analysis, and visualization using Pandas and Matplotlib.

---

## 📌 Project Overview

The project demonstrates how sales data can be loaded, explored, cleaned, analyzed, and visualized using **Pandas** and **Matplotlib**.

It provides a simple menu-driven interface for performing common data analysis tasks and generating meaningful visualizations.

---

## 🎯 Objectives

- Load and explore sales data from a CSV file.
- Perform data manipulation using Pandas.
- Search, sort, and filter records.
- Handle missing values.
- Perform mathematical and statistical operations.
- Create Pivot Tables.
- Use `groupby()` and `transform()`.
- Generate different types of visualizations.
- Save visualizations as PNG files.

---

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming Language |
| Pandas | Data Analysis & Manipulation |
| Matplotlib | Data Visualization |
| CSV | Dataset Format |
| Jupyter Notebook / VS Code | Development Environment |
| Git & GitHub | Project Management |

---

## 📂 Project Structure

```text
Project-9/
│
├── project9.ipynb
├── sales_data.csv
├── README.md
└── scatter_plot.png

## 📄 File Description

project9.ipynb	Cell-wise notebook implementation
sales_data.csv	Sample sales dataset
README.md	Project documentation
scatter_plot.png	Saved visualization

📊 Dataset

The project uses sales_data.csv.

Columns
Column	Description
SalesID	Unique sales record ID
Product	Product category
Region	Sales region
Sales	Sales amount
Year	Year of sale

✨ Features

📥 Load CSV Dataset
🔍 Explore Data
🔎 Search Records
↕️ Sort Data
🎯 Filter Data
➕ Perform Mathematical Operations
✂️ Split Data
🔗 Combine DataFrames
📋 Create Pivot Tables
🔄 Re-index Data
👥 GroupBy Analysis
🧮 Transform Operations
🧹 Handle Missing Data
📈 Generate Descriptive Statistics
📊 Create Visualizations
💾 Save Visualizations

🧹 Missing Data Handling

The project provides options to:
Display rows containing missing values
Fill missing numerical values with mean
Drop rows containing missing values
Replace missing values with a specific value

Example:
df["Sales"] = df["Sales"].fillna(df["Sales"].mean())

📈 Statistical Analysis

Descriptive statistics are generated using Pandas.
df.describe()
The project can calculate:
Mean
Sum
Count
Minimum
Maximum
Standard Deviation
Quartiles

📊 Data Visualization

The project uses Matplotlib to create:
Chart	Purpose
Bar Plot	Compare categories
Line Plot	Show trends
Scatter Plot	Show relationships
Pie Chart	Show proportions
Histogram	Show data distribution
Stack Plot	Compare cumulative values

Charts can be customized with titles, labels, legends, and appropriate figure sizes.

💾 Save Visualization

Generated plots can be saved as PNG files.
Example:
plt.savefig(
    "scatter_plot.png",
    dpi=300,
    bbox_inches="tight"
)

🧭 Application Menu

==================================================
     DATA ANALYSIS & VISUALIZATION PROGRAM
==================================================

1. Load Dataset
2. Explore Data
3. Perform DataFrame Operations
4. Handle Missing Data
5. Generate Descriptive Statistics
6. Data Visualization
7. Save Visualization
8. Exit

🔄 Project Workflow

Load Dataset
     ↓
Explore Data
     ↓
Clean Data
     ↓
Manipulate Data
     ↓
Analyze Data
     ↓
Visualize Data
     ↓
Save Results

🚀 Installation

1. Check Python
python --version
2. Install Required Libraries
pip install pandas matplotlib
Or:
python -m pip install pandas matplotlib

▶️ Run the Project

When asked for the dataset path, enter:
sales_data.csv
Jupyter Notebook

Open:
project9.ipynb

Run the cells from top to bottom.

🧪 Example

To create a Scatter Plot:
Main Menu
   ↓
6. Data Visualization
   ↓
3. Scatter Plot
   ↓
X-axis: Sales
Y-axis: Year

To save the plot:
Main Menu
   ↓
7. Save Visualization
   ↓
scatter_plot.png

💡 Analysis Insights

The project can be used to identify:
Total and average sales
Highest and lowest sales
Product-wise performance
Region-wise performance
Year-wise sales trends
Sales distribution
High-value sales records

Actual insights depend on the dataset provided.

📌 Assumptions

Input data is provided in CSV format.
Column names are entered correctly.
Sales contains numerical values.
Year contains valid year values.
Product and Region are categorical columns.
Generated CSV files and visualizations are saved in the current working directory.

🔮 Future Scope

The project can be extended with:
Interactive dashboards using Streamlit
Advanced visualizations using Seaborn or Plotly
Excel/PDF report generation
Sales forecasting
Machine Learning prediction
Interactive filters
Automated business insights

🧠 Learning Outcomes

This project provides practical experience with:

Python

Functions
Loops
Conditions
User Input
Menu-driven Programming

Pandas

DataFrames
CSV Handling
Filtering
Sorting
GroupBy
Transform
Pivot Tables
Missing Values
Statistical Analysis

Matplotlib

Bar Plot
Line Plot
Scatter Plot
Pie Chart
Histogram
Stack Plot
Saving Figures

👩‍💻 Author

Vaibhavi Khokhani
BCA Graduate | Python & AI Learner
