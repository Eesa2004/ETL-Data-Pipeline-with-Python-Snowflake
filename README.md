# ETL Data Pipeline with Python and Snowflake

## Overview

This project demonstrates my ability to build a robust ETL (Extract, Transform, Load) data pipeline using Python and Snowflake. It was completed as part of a challenge for Digital Native, showcasing my skills in data engineering, data cleaning, and cloud data warehousing.

---

## Skills Demonstrated

- **Data Extraction:** Loaded raw CSV data into a Jupyter Notebook using Pandas.
- **Data Transformation:** Performed comprehensive data cleaning, including:
  - Handling missing values and outliers
  - Resolving inconsistent categorical values
  - Renaming and reformatting columns
  - Ensuring data quality and integrity
- **Data Loading:** Connected to Snowflake using Snowpark and securely loaded the cleaned data into a cloud database table.
- **Python Programming:** Utilized Pandas for data manipulation and Snowflake’s Snowpark library for cloud integration.
- **Environment Management:** Created and managed a dedicated Conda environment for reproducibility and dependency management.
- **Documentation:** Clearly explained the ETL process in both a Jupyter Notebook and a PowerPoint presentation (see below).

---

## ETL Process

1. **Extract:**  
   - Imported the dataset (`used_cars_UK.csv`) into a Pandas DataFrame.

2. **Transform:**  
   - Explored the data (shape, info, missing values, outliers, duplicates).
   - Cleaned the data by:
     - Removing or imputing missing values
     - Filtering outliers using the IQR method
     - Standardizing categorical values (case, whitespace)
     - Renaming columns for consistency

3. **Load:**  
   - Established a secure connection to Snowflake.
   - Created a new database and table.
   - Uploaded the cleaned DataFrame to Snowflake using Snowpark.

---

## Documentation

- **Jupyter Notebook:**  
  The ETL process is documented step-by-step in the notebook `ETL_Data_Pipeline_with_Python.ipynb`, with code, outputs, and concise explanations.
- **PowerPoint Presentation:**  
  The project workflow, challenges, and solutions are explained in detail in the PowerPoint deck for clear communication and reporting.

---

## Challenge Completion

This project was completed as part of a Digital Native challenge, demonstrating my ability to solve real-world data engineering problems and communicate results effectively.

---

## Environment Setup

A dedicated Conda environment was created to ensure reproducibility:

```bash
conda create -n etl_snowflake python=3.10 pandas snowflake-snowpark-python jupyter
conda activate etl_snowflake
```

---

## How to Run

1. Clone the repository.
2. Activate the Conda environment.
3. Open the Jupyter Notebook and follow the documented steps.

---

## Contact

For questions or collaboration, please reach out via GitHub or LinkedIn.