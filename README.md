# Job Search Platform Efficacy Analysis

This project explores a 100,000-row dataset on job search behavior and outcomes for students. The analysis is built in a Jupyter notebook and focuses on how factors such as GPA, internships, extracurricular activities, networking, search platforms, and application volume relate to interview and offer outcomes.

## Project Files

- `job_search.ipynb` - main notebook containing data loading, cleaning, exploratory analysis, visualizations, and findings
- `job_search_platform_efficacy_100k.csv` - dataset used for the analysis

## Dataset

The dataset contains 20 columns and 100,000 records covering:

- student background and profile features
- university and region information
- job search behavior
- interview progression
- offer outcomes and salary details

The notebook also notes that some missing values are meaningful, especially for records where no job offer was received.

## Tools and Libraries

The analysis uses:

- pandas
- numpy
- matplotlib
- seaborn
- plotly
- requests

## What the Notebook Covers

- loading the dataset from a remote CSV source or local file
- inspecting shape, columns, data types, duplicates, and missing values
- summary statistics and correlation analysis
- visual exploration of numerical relationships
- investigation of offer outcomes for candidates who did and did not receive offers

## How to Run

1. Open `job_search.ipynb` in Jupyter Notebook, JupyterLab, or VS Code.
2. Make sure the CSV file is available in the same folder, or update the path in the data-loading cell.
3. Run the notebook cells from top to bottom.

## Notes

The notebook is written as an exploratory data analysis project for an AI and Applications course context. It is intended to help interpret job-search platform effectiveness and related hiring patterns.
