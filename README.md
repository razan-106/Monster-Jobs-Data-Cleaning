# Monster.com Job Market Data Cleaning & ETL

##  Project Overview
This project demonstrates a full ETL (Extract, Transform, Load) process on a raw dataset containing 22,000+ job postings from Monster.com. The goal was to transform unstructured, "dirty" data into a clean, structured format ready for analysis.

##  Tech Stack
- **Language:** Python
- **Libraries:** Pandas, NumPy, Re (Regex), Matplotlib, Seaborn
- **Database:** SQLite

##  Key Features
- **Salary Standardization:** Converted complex salary strings (hourly/yearly) into a unified annual numeric scale.
- **Location Intelligence:** Parsed messy location strings into separate `City` and `State` columns.
- **Data Quality:** Handled missing values (NaNs) and removed redundant/empty columns (like `date_added`).
- **Text Processing:** Cleaned job descriptions from HTML tags and special characters using Regex.

##  Dataset Source
The raw dataset used in this project can be found on Kaggle: 
[Link to Kaggle Dataset](https://www.kaggle.com/code/ankkur13/perfect-dataset-to-get-the-hands-dirty/input)

##  Files in this Repository
- `Monster_Jobs_Cleaning.ipynb`: The full Python source code and analysis.
- `monster_jobs_sample_cleaned.csv`: A sample of the final cleaned data (500 rows).
