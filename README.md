# Data-Cleaning-and-Preprocessing
Cleaned a raw dataset using Python and Pandas by handling missing values, removing duplicates, standardizing text, converting dates, and renaming columns for consistency. Prepared the data for analysis with a clean, structured output saved as a CSV file. Full process documented in a Jupyter Notebook.
# Task 1 : Data Cleaning and Preprocessing
# Kaggle Database : https://storage.googleapis.com/kaggle-data-sets/4538199/7760004/compressed/netflix_titles.csv.zip?X-Goog-Algorithm=GOOG4-RSA-SHA256&X-Goog-Credential=gcp-kaggle-com%40kaggle-161607.iam.gserviceaccount.com%2F20250602%2Fauto%2Fstorage%2Fgoog4_request&X-Goog-Date=20250602T145611Z&X-Goog-Expires=259200&X-Goog-SignedHeaders=host&X-Goog-Signature=7944313b460282fede4ef75ab0a123bcaade0b40413dd91c4af44c4dd95a50eb651928f5261934e7a4fae008d5d3a0e0afe00ef938022bd18471b91a604c509a69e19f28d733210234c72645b7ccba9d25c786bdf832fbdf84709e77056c7d3e4b6f8b5177fe83d22a8aea3466844a73aa9bf04c18d0a81ddc9e0767d862ea820d131542587f7a0561042247df95fa9a845bf88c2a11558ae81d4d09e000065ad50fa27551fea06a51d8baad16483c2b68b7ad8220222a8beeda29113cc65a559b77d22cb13411f4b18d11481b15ad163be012655e9282771aab9e76007b2f00122c95a24ac53fa009a5c3cccbb7a60490732fb1ce8092b94612cc45285961d3
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
