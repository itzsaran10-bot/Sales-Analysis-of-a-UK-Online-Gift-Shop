# Exploratory Data Analysis and Data Visualization Using Python

An analysis of one year of sales from a UK online gift shop (Online Retail II dataset), done with Python, Pandas, NumPy, Matplotlib and Seaborn. The project covers data cleaning, exploratory analysis, statistics, charts, and business recommendations.

## Files in this repository

| File | Description |
|---|---|
| `Online_Retail_EDA_Project.ipynb` | Python notebook with the full analysis and charts |
| `cleaned_dataset.zip` | Cleaned dataset (zipped CSV file) |
| `Project_Report.pdf` | Project report |
| `Project_Presentation.pptx` | PowerPoint presentation |

## Dataset

Online Retail II (sheet `Year 2010-2011`): sales of a UK online gift shop, from 1 December 2010 to 9 December 2011. Each row is one product on one order, and all amounts are in British pounds (£). The raw data has 541,910 rows, and 524,877 rows remain after cleaning.

The dataset is available on Kaggle. The original file is not included in this repository because of its size.

## What was done

1. Imported and inspected the data
2. Cleaned it (missing values, duplicates, cancelled orders, zero or negative values, extreme orders)
3. Created `revenue` and `Month` columns
4. Explored it with Pandas and calculated statistics with NumPy
5. Built 6 charts with Matplotlib and Seaborn
6. Wrote the insights and recommendations

## Key findings

- The UK brings in about 84% of the total revenue of £10.4 million.
- Sales peak from September to November.
- Most orders are small, but a few bulk orders are very large.
- Cheap, small items are the best sellers.
- Price does not decide how much is bought.

## How to run

1. Install the libraries: `pip install pandas numpy matplotlib seaborn openpyxl`
2. Download the Online Retail II dataset (`online_retail_II.xlsx`) from Kaggle and keep it in the same folder as the notebook.
3. Change the file path in the notebook's import cell to match your folder.
4. Open the notebook and run all cells.

## Author

**SARAN KUMAR.M**
GitHub: [itzsaran10-bot](https://github.com/itzsaran10-bot)
