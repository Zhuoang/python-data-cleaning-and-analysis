# Python Data Cleaning & Analysis
This repository showcases practical data cleaning and exploratory analysis projects using **Python (pandas, NumPy, matplotlib, seaborn)**. It includes end-to-end workflows from raw, messy data to actionable insights, demonstrating skills in **data wrangling, feature engineering, and exploratory analysis**.

---

## 📊 Projects

### 1. Cafe Sales Data Cleaning

**Goal**: Demonstrate data cleaning techniques on a raw point-of-sale dataset.  
**Highlights**:

- Reconstructed and cleansed transaction data using rule-based imputation, type correction, and feature engineering.  
- Handled duplicates, missing values, and inconsistent product categories.  
- Prepared a clean dataset for profitability and sales behaviour analysis.  

📂 Files:

- `cafe_sales_cleaning.ipynb` – Data wrangling and transformation workflow.  

---

### 2. Superstore Sales Analysis
**Goal**: Analyze sales and profitability patterns using the clean, analysis-ready Superstore dataset.  

**Highlights**:
- Computed key metrics (sales, profit, profit margin, average order value) using pandas groupby.
- Explored trends and comparisons by time, region, customer segment, and product category (ranking & contribution analysis).
- Produced clear visualizations to surface top drivers and underperforming segments.

📂 Files:
- `superstore_analysis.ipynb` – Exploratory analysis and visualization.

---

## 🛠️ Skills Demonstrated
- **Data Cleaning**: handling missing values, duplicates, type conversions.  
- **Feature Engineering**: deriving profitability, date features, customer segments.  
- **Exploratory Analysis**: groupby operations, descriptive statistics, visualizations.  
- **Tools**: Python (pandas, NumPy, matplotlib, seaborn, sklearn).  

---

## 📂 Repository Structure

```
python-data-cleaning-and-analysis/
│
├── cafe-sales-data-cleaning/         # Project 1: Cafe Sales Cleaning
│  ├── datasets/                      
│  │  ├── cleansed_cafe_sales.csv     # Raw sales dataset
│  │  └── raw_cafe_sales.csv          # Cleaned dataset
│  ├── scripts/                       
│  │  └── cafe_sales_cleaning.ipynb   # Data cleaning workflow
│  └── README.md                      # Project description and usage
│
├── superstore-sales-analysis/        # Project 2: Superstore Sales Analysis
│  ├── datasets/
│  │  └── superstore.csv              # Superstore dataset
│  ├── scripts/
│  │  └── superstore_analysis.ipynb   # Analysis and visualization
│  └── README.md                      # Project description and usage
│
├── .gitignore                        # Files and directories to ignore in Git
├── LICENSE                           # License information
└── README.md                         # Project overview and instructions
```
