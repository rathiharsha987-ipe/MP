
# Seasonal Agriculture Performance Analysis

## VOIS AICTE Batch 1 2026–2027

A data analytics project that explores agricultural performance across different seasons, crops, states, irrigation methods, environmental conditions, and economic factors.

---

## Project Overview

Agricultural performance varies due to seasonal changes, environmental conditions, farming practices, resource availability, and market conditions.

This project analyzes agricultural data to identify meaningful patterns, trends, relationships, and differences in agricultural performance across seasons.

The analysis is performed using Python and Jupyter Notebook.

---

## Problem Statement

Raw agricultural data does not clearly explain how agricultural performance changes across seasons or what patterns can be observed under different seasonal conditions.

The objective of this project is to analyze the given agricultural dataset and investigate seasonal differences in yield, production, resource usage, and economic performance.

---

## Objectives

- Explore and understand the agricultural dataset.
- Clean and prepare the data for analysis.
- Analyze agricultural performance across seasons.
- Compare crop-wise and state-wise performance.
- Examine irrigation methods and water efficiency.
- Study relationships between environmental conditions and agricultural outcomes.
- Apply statistical and visualization techniques.
- Identify meaningful findings and patterns.
- Develop evidence-based recommendations.

---

## Dataset Description

The dataset contains agricultural records covering different farming conditions and performance indicators.

### Dataset Details

| Feature | Description |
|---|---|
| Dataset Name | Seasonal Agriculture Performance Dataset |
| Records | 4,000 |
| Features | 28 |
| Seasons | Kharif, Rabi, Zaid |
| Crops | 8 crop categories |
| States | 8 states |
| Irrigation Methods | 4 methods |
| Format | CSV |

### Important Variables

- Season
- Crop
- State
- Irrigation_Method
- Rainfall_mm
- Avg_Temperature_C
- Humidity_pct
- Soil_Moisture_pct
- Fertilizer_kg_ha
- Yield_Tonnes_Ha
- Production_Tonnes
- Market_Price_INR_Tonne
- Total_Cost_INR
- Revenue_INR
- Profit_INR
- Water_Used_m3
- Water_Efficiency_t_per_1000m3
- Disease_Pest_Risk_pct

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- SciPy
- Jupyter Notebook
- VS Code

---

## Project Workflow

1. Import required Python libraries.
2. Load the agricultural CSV dataset.
3. Explore the dataset and its structure.
4. Check missing values and duplicate records.
5. Clean and prepare the data.
6. Perform seasonal performance analysis.
7. Analyze crop-wise and state-wise performance.
8. Compare irrigation methods and water efficiency.
9. Study relationships using correlation analysis.
10. Apply statistical tests.
11. Generate visualizations.
12. Develop findings, conclusions, and recommendations.

---

## Data Cleaning

The following data preparation steps were performed:

- Duplicate records were checked and removed.
- Numerical missing values were handled using median imputation.
- Categorical missing values were handled using mode imputation.
- Important categorical variables were inspected.
- The cleaned dataset was used for further analysis.

---

## Analysis Performed

### 1. Seasonal Analysis

Comparison of:

- Average yield
- Average production
- Average revenue
- Average cost
- Average profit
- Rainfall
- Water efficiency
- Disease and pest risk

### 2. Crop-wise Analysis

Comparison of crop categories based on:

- Average yield
- Average profit
- Production
- Water efficiency

### 3. State-wise Analysis

Comparison of agricultural performance across different states.

### 4. Irrigation Analysis

Study of irrigation methods using:

- Average yield
- Average profit
- Water usage
- Water efficiency

### 5. Correlation Analysis

Relationships between:

- Fertilizer use and yield
- Rainfall and yield
- Environmental conditions and agricultural outcomes
- Economic and production variables

### 6. Statistical Analysis

The project applies:

- One-way ANOVA
- Kruskal–Wallis test

These tests investigate whether agricultural yield differs significantly across seasons.

---

## Visualizations

The project includes:

- Season-wise record distribution
- Crop-wise record distribution
- State-wise record distribution
- Irrigation method distribution
- Average yield by season
- Average profit by season
- Average yield by crop
- Average profit by crop
- Average yield by state
- Season × Crop yield heatmap
- Irrigation yield comparison
- Water efficiency comparison
- Fertilizer vs Yield scatter plot
- Rainfall vs Yield scatter plot
- Correlation heatmap

---

## Key Findings

The notebook automatically calculates the main findings from the cleaned dataset.

These include:

- Season with the highest average yield.
- Season with the highest average profit.
- Crop with the highest average yield.
- Crop with the highest average profit.
- State with the highest average yield.
- Best-performing irrigation method.
- Water efficiency comparison.
- Correlation between fertilizer use and yield.
- Correlation between rainfall and yield.
- Statistical significance of seasonal yield differences.

> Note: Exact numerical findings should be updated after running the final Jupyter Notebook.

---

## Recommendations

Based on the analysis, the project provides recommendations related to:

- Seasonal agricultural planning.
- Crop selection.
- Irrigation and water management.
- Resource allocation.
- Disease and pest risk monitoring.
- Agricultural performance improvement.

The recommendations are based on patterns observed in the available dataset.

---

## Project Files

```text
Seasonal-Agriculture-Performance-Analysis/
│
├── VOIS_Analysis_Project_SA.ipynb
├── seasonal_agriculture_performance_dataset.csv
├── Seasonal_Agriculture_Analysis_Results.xlsx
└── README.md
```

---

## How to Run the Project
### Step 1: Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn scipy openpyxl
```

### Step 2: Open the Notebook

Open the `.ipynb` file in:

- VS Code with Jupyter extension, or
- Jupyter Notebook.

### Step 3: Run All Cells

Execute the notebook cells from top to bottom to reproduce the analysis and generate results.

---

## Output

The project generates:

- Cleaned agricultural dataset.
- Seasonal summary tables.
- Crop-wise performance tables.
- State-wise performance tables.
- Irrigation analysis.
- Statistical test results.
- Data visualizations.
- Evidence-based findings and recommendations.
- Excel file containing analysis results.

---

## Future Scope

- Develop an interactive Power BI dashboard.
- Apply machine learning for yield prediction.
- Develop seasonal agricultural forecasting models.
- Optimize irrigation and fertilizer allocation.
- Integrate real-time weather data.
- Build a decision-support system for farmers.
- Extend the analysis using larger real-world datasets.

---

## Limitations

- The analysis is based on the available dataset.
- Correlation does not establish causation.
- Statistical significance does not necessarily imply practical significance.
- Results may depend on crop mix, region, and other farming conditions.
- Further real-world validation is required before applying recommendations.

---

## Author

**Harsha Rathi**

B.Tech Industrial & Production Engineering  
SGSITS, Indore

---

## Acknowledgement

This project was completed as part of the VOIS AICTE Batch 1 2026–2027 Major Project.

The project focuses on applying Python-based data analytics and visualization techniques to a real-world agricultural performance problem.

---

## License

This project is created for educational and academic purposes.