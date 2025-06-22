Athlete Biographical Data Analysis

This project involves cleaning, transforming, and analyzing a dataset of international athletes using Python and Pandas.

Dataset
- File: `bios.csv`
- Type: CSV
- Fields include athlete name, height, birthplace, birthdate, and more

Tools Used
- Python 3.10.11
- Pandas
- Jupyter Notebook

Project Steps

1. Data Loading & Initial Exploration
   - Loaded CSV into a DataFrame using `pd.read_csv()`
   - Checked null values, structure, and sample rows

2. Filtering
   - Filtered by height > 215 cm
   - Filtered by birthplace (country, city)
   - Regex filtering for names (e.g., "Keith", "Patrick")

3. Feature Engineering
   - Extracted `first_name` from full names
   - Converted `born_date` to `datetime` format
   - Created `born_year` column


5. Output
   - Saved cleaned dataset as `bios_new.csv`

Key Insights

- Tallest athletes identified across countries
- Seattle and specific U.S. states were major contributor regions
- Extracted clean year-based insights from raw date data

Files in This Repo

-  README.md
- `bios.csv`: Original dataset
- `bios_analysis.ipynb`: Jupyter Notebook with analysis
- `bios_new.csv`: Cleaned and enriched dataset

Author
Contributed by: Divya Bariya
(Hands-on implementation based on publicly available learning content)
