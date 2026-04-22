# Promotion Effectiveness Analysis in FMCG

## Project Overview

This project examines the effectiveness of promotions in the fast-moving consumer goods (FMCG) sector using Python-based data analysis. The main objective is to evaluate whether promotional activities are associated with changes in sales and revenue, and to provide business insights for decision-making.

The project was developed as a GitHub Data Analysis Project for ACC102 Mini Assignment (Track 2). The analysis focuses on building a clear and reproducible workflow from raw data input to cleaned data, descriptive analysis, visualisation, and final business interpretation. 

## Analytical Problem

Promotions are widely used in FMCG markets to increase product visibility and stimulate demand. However, promotions may not always lead to better business outcomes. The key analytical question in this project is:

**Do promotions improve sales and revenue performance in the FMCG dataset?**

This project is designed for a business-oriented audience, such as marketing managers, retail analysts, or decision-makers who want to understand whether promotional strategies are associated with measurable performance differences.

## Dataset

This project uses the following source files:

- `data/sales.csv`
- `data/product_hierarchy.csv`

The main analysis in the notebook is based on `sales.csv`, which contains transaction-related variables such as sales, revenue, stock, price, date, and promotion-related fields.

The `product_hierarchy.csv` file is included as a supporting dataset, although the main notebook analysis and visual outputs are primarily based on the sales dataset.

## Data Source Note

The dataset was selected because it is relevant to a business and marketing context and is suitable for demonstrating Python-based data cleaning, transformation, descriptive analysis, and visualisation. The source and access details should also be stated in the notebook or reflection report, as required in the assignment brief. 

## Methods Used

The notebook follows a coherent analytical workflow, including:

1. **Problem definition**
2. **Data loading**
3. **Data cleaning and preparation**
4. **Feature creation**
5. **Exploratory data analysis**
6. **Visualisation**
7. **Interpretation of findings**
8. **Summary and conclusion**

The main Python methods used include:

- reading CSV files with `pandas`
- handling missing values
- converting data types
- creating a promotion indicator variable (`is_promoted`)
- filtering invalid observations
- summarising key variables
- generating charts for comparison and interpretation

This structure follows the assignment expectation that the notebook should show a complete analytical workflow from data input to final output. 

## Key Analysis Steps

### 1. Data Cleaning
The raw sales data were cleaned by:
- converting the date column into datetime format
- converting selected columns into numeric format
- checking and handling missing values
- removing invalid negative values in key variables
- creating a promotion flag variable based on promotion-related columns

### 2. Feature Engineering
A binary variable named `is_promoted` was created to indicate whether a product observation was associated with promotional activity.

### 3. Exploratory Analysis
The notebook compares promotional and non-promotional observations using descriptive statistics and visualisations.

### 4. Visualisation
Charts were used to examine distributions and differences in sales and revenue, helping communicate the analytical results more clearly to the intended audience.

## Main Findings

The notebook suggests that promotional status is associated with differences in business performance indicators such as sales and revenue. The exact interpretation should be based on the outputs presented in the notebook, but overall the project provides a data-driven view of promotion effectiveness in the FMCG context.

The analysis supports the idea that Python can be used not only for technical data processing but also for generating practical business insights.

## Files Included

This repository contains:

- `README.md` – project overview and instructions
- `*.ipynb` – Python notebook showing the full workflow
- `data/sales.csv` – raw sales dataset
- `data/product_hierarchy.csv` – supporting product hierarchy dataset
- other related project files if applicable

## File Note on Cleaned Dataset

The cleaned dataset was not uploaded separately because of file size limitations.

However, all data cleaning, transformation, and analysis steps are fully documented in the notebook. The entire workflow is reproducible by running the notebook from the original raw data files provided in the `data` folder.

If needed, the cleaned dataset can be regenerated directly by running the export code included in the notebook.

## How to Run the Project

1. Download or clone this repository.
2. Make sure the required data files are stored in the `data` folder:
   - `sales.csv`
   - `product_hierarchy.csv`
3. Open the notebook in Jupyter Notebook or JupyterLab.
4. Run the cells in order from top to bottom.

## Requirements

The project uses Python and common data analysis libraries, including:

- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`

Please make sure these packages are installed before running the notebook.

## Limitations

This project has several limitations:

- the analysis is based on the available variables in the dataset only
- promotion effectiveness is evaluated mainly through descriptive analysis
- other external factors that may influence sales are not fully modelled
- the supporting product hierarchy dataset was not deeply integrated into the final analysis workflow

These limitations should be considered when interpreting the findings.

## Conclusion

This project demonstrates a small Python-based data product that addresses a clear business question in the FMCG sector. By combining data cleaning, transformation, visualisation, and interpretation, the notebook provides a practical example of how Python can support business analysis and communication.

## Assignment Context

This repository was created for ACC102 Mini Assignment, Track 2: GitHub Data Analysis Project. According to the assignment requirements, Track 2 submissions should include a GitHub project, Python notebook or code files, a README, a 1–3 minute demo video, and a reflection report. All submitted materials must be in English. 
