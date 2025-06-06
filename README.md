# Data-Cleaning-and-Preprocessing
Cleaned a raw dataset using Python and Pandas by handling missing values, removing duplicates, standardizing text, converting dates, and renaming columns for consistency. Prepared the data for analysis with a clean, structured output saved as a CSV file. Full process documented in a Jupyter Notebook.
# Task 1 : Data Cleaning and Preprocessing
# Objective
    The goal of this task was to clean and preprocess a raw dataset to make it suitable for analysis. This involved identifying and resolving common data issues such as null values, duplicates, inconsistent formats, and improper column naming.

# Tools Used :
        Python
        
        Jupyter Notebook
        
        Pandas

# Description :
    The dataset was loaded into a Jupyter Notebook using Pandas. An initial exploration was done to understand the structure and identify issues. Missing values were handled by either filling them with appropriate values or dropping them based on relevance. Duplicate rows were detected and removed to prevent redundancy.
    
    Text columns were standardized by converting them to lowercase or title case as needed. Date columns (like date_added) were converted to a proper datetime format using pd.to_datetime(), ensuring consistency across the dataset. Column names were cleaned and formatted to follow a consistent naming convention (e.g., replacing spaces with underscores and using lowercase letters).
    
    After applying all transformations, the cleaned dataset was saved as a new CSV file. These changes improve the quality and usability of the data for future analysis or machine learning tasks.

# Summary of Changes :
    1.Removed duplicates
    
    2.Handled missing values
    
    3.Standardized text formats
    
    4.Converted and cleaned date columns
