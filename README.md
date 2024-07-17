# -COFI_PowerPlay_Analysis
Analysis of Global Energy Investments in BRI Countries.
# COFI PowerPlay: Analyzing Global Energy Investments

## Introduction

"COFI PowerPlay: Analyzing Global Energy Investments" is an engaging and instructive case study designed for data science trainees. It delves into the complex world of global energy sector investments, focusing specifically on projects financed by Chinese entities under the Belt and Road Initiative (BRI). The study utilizes data from the China Overseas Finance Inventory (COFI) Database, which records diverse types of investments in power-generation projects across BRI countries.

## Dataset

The COFI Database offers detailed insights into numerous power projects funded by Chinese investments. It includes crucial data points such as:
- **Project details**: Names, locations, and characteristics of power plants.
- **Financial information**: Types of financing (debt or equity), amounts invested, and the financial closure year of these investments.
- **Energy specifics**: Installed capacity, type of energy (coal, solar, wind, etc.), and the operational status of each project.

Dataset source: [COFI Database on Kaggle](https://www.kaggle.com/datasets/shivavashishtha/china-overseas-finance-inventory-database/data)

## Analytical Objectives

Participants in this case study will analyze the dataset to:
1. Identify patterns and trends in the types of investments made over the years.
2. Evaluate the focus on renewable versus non-renewable energy projects.
3. Assess the geographical distribution of investments and their alignment with sustainability goals.

## Data Cleaning and Preprocessing

### Steps:
1. **Check for and Handle Missing Values**: Identify and address missing values.
2. **Correct Data Types**: Ensure numerical, date, and categorical fields have correct data types.
3. **Standardize Categories**: Ensure consistency in naming conventions.
4. **Remove Duplicates**: Identify and remove duplicate rows.
5. **Filter Out Irrelevant Data**: Focus on relevant records for analysis.
6. **Create Derived Variables**: Enrich the dataset with new columns based on existing data.
7. **Handle Outliers**: Detect and manage outliers in critical numerical columns.
8. **Validate Accuracy**: Perform spot checks and validate key entries.
9. **Document Changes**: Keep a changelog for tracking changes.

## Data Visualization and Analysis

Using Google Looker Studio, various KPIs and visualizations will be created:

1. **Total Investment Over Time**: Line Chart
2. **Investment Distribution by Energy Type**: Pie Chart
3. **Geographical Distribution of Investments**: Geo Map
4. **Average Investment Size by Energy Type**: Bar Chart
5. **Analysis of Investment Complexity by Number of Lenders**: Histogram/Box Plot
6. **Renewable vs Non-Renewable Investment Ratio**: Stacked Bar Chart
7. **Debt and Equity Investment Trends Over Time**: Line Chart
8. **Capacity Installation Trends**: Area Chart
9. **Analysis of Investment by Region and Subregion**: Treemap/Geo Map/Bar Chart
10. **Number of Projects by Energy Type**: Column Chart

## Real-World Applications

The insights derived from this analysis are crucial for stakeholders in the energy sector, including policymakers, investors, and environmental groups. They provide a basis for making informed decisions regarding future investments, policy-making for sustainable development, and strategic planning for transitioning to greener energy alternatives.

## Repository Structure

```plaintext
COFI_PowerPlay_Analysis/
│
├── data/
│   ├── raw/                # Raw dataset files
│   ├── cleaned/            # Cleaned and preprocessed data files
│
├── notebooks/
│   ├── data_cleaning.ipynb # Notebook for data cleaning and preprocessing
│   ├── analysis.ipynb      # Notebook for analysis and visualizations
│
├── reports/
│   ├── COFI_PowerPlay_Analysis.pdf # Final report
│
├── README.md               # Project overview and instructions
└── requirements.txt        # List of dependencies
