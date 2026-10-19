# YuvaIntern-Week1-Data-Exploration
Week 1: Data Exploration and Problem Definition using Python and the UCI Online Retail dataset.

# Week 1: Data Exploration and Problem Definition

## Project Overview
This project explores the UCI Online Retail dataset using Python. The objective is to understand the dataset structure, assess data quality, identify unusual values, visualize distributions, and define business questions for further analysis.

## Dataset
- **Source:** [UCI Machine Learning Repository — Online Retail](https://archive.ics.uci.edu/dataset/352/online%2Bretail)
- **Original records:** 541,909 rows
- **Original columns:** 8
- **Additional feature:** Revenue, calculated as Quantity × UnitPrice
- **Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn

## Work Performed
1. Inspected the dataset structure and data types.
2. Generated descriptive statistics.
3. Identified missing values and duplicate rows.
4. Checked negative quantities and zero or negative unit prices.
5. Converted invoice dates to datetime format.
6. Created revenue and analyzed revenue by country and month.
7. Visualized quantity, unit price, country revenue, and monthly revenue.

## Initial Data Quality Findings
- Total records: 541,909
- Missing values: 136,534 across the dataset
- Duplicate rows: 5,268
- Missing CustomerID values: 135,080
- Negative quantity rows: 10,624
- Zero UnitPrice rows: 2,515
- Negative UnitPrice rows: 2
- Date range: December 2010 to December 2011

These are initial findings. Negative quantities may represent returns or credit transactions, so they require investigation before removal. Missing customer identifiers may limit customer-level analysis.

## Business Questions
- Which countries generate the most revenue?
- How does revenue change over time?
- Which data quality issues could affect the analysis?
- How can missing values and unusual transactions be handled responsibly?

## Limitations and Next Steps
The initial analysis does not establish that all transactions represent completed sales. Future work should investigate cancellations and returns, document cleaning decisions, validate revenue calculations, and compare results before and after cleaning.

## Repository Contents
- `Week1_Data_Exploration.ipynb` — exploration notebook
- `EDA_Findings.txt` — summary of initial findings
- `Country_Revenue_Analysis.csv` — country-level analysis
- `Monthly_Revenue_Analysis.csv` — monthly analysis
- `Top_10_Countries_Revenue.png` — country revenue chart
- `Monthly_Revenue_Trend.png` — monthly revenue chart
- `YuvaIntern_Week1_Data_Exploration_Report.docx` — Word report

## Author
Subhash Kumar Paswan

*This project was completed as part of the YuvaIntern Data Analytics Internship, Week 1 task.*
