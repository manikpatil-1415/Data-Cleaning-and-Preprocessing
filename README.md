# Data Cleaning and Preprocessing – Task 1

## Objective
Clean and prepare a raw supermarket sales dataset by identifying and handling missing values, duplicate records, inconsistent formats, and data quality issues.

## Tools Used
- Python
- Pandas
- Google Colab

## Dataset
The project uses supermarket sales data divided into four annex datasets:
- annex1
- annex2
- annex3
- annex4

## Data Cleaning Steps
- Checked dataset columns, rows, and data types
- Identified missing values
- Handled invalid time values
- Removed duplicate rows
- Standardized column names
- Checked numerical columns for possible outliers
- Checked sales/return and discount values
- Verified the cleaned datasets for remaining missing values

## Cleaning Results

| Dataset | Rows | Columns | Missing Values | Duplicate Rows |
|---|---:|---:|---:|---:|
| annex1 | 251 | 4 | 0 | 0 |
| annex2 | 878,503 | 7 | 0 | 0 |
| annex3 | 55,982 | 3 | 0 | 0 |
| annex4 | 251 | 3 | 0 | 0 |

## Special Data Quality Finding
In annex2, 132 invalid/missing time values were identified and corrected during preprocessing.

There were also 461 negative quantity records. These records were associated with `return` transactions.

## Deliverables
- Python data cleaning notebook
- Cleaned CSV datasets
- Short summary of data cleaning and preprocessing

## Note
The cleaned annex2 dataset is larger than GitHub's standard 25 MB web upload limit, so it is not uploaded directly through the GitHub web interface.
