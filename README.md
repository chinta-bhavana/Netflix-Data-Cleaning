# Netflix-Data-Cleaning

📌 Project Title

Netflix Data Cleaning and Preprocessing

📊 Project Description

This project focuses on cleaning and preprocessing the Netflix Movies and TV Shows dataset using Python and Pandas.

🛠️ Steps Performed

- Loaded the Netflix dataset using Pandas

- Explored the dataset using info() and isnull() to understand structure and missing values

- Handled missing values in columns like director, cast, country, rating, duration using appropriate techniques

- Treated missing values in date_added using forward fill method (ffill())

- Removed duplicate records using drop_duplicates()

- Standardized column names by converting them to lowercase and replacing spaces with underscores

- Converted date_added column to proper datetime format for time-based analysis

- Cleaned and standardized categorical columns like type and country

- Split the duration column into duration_value and duration_type for better usability

- Converted data types of columns such as release_year and duration_value to numeric formats

- Performed final data quality checks to ensure no missing values and correct data types

- Saved the cleaned dataset as cleaned_netflix.csv for further analysis

📁 Files Included

- Netflix_Dataset.csv→ Raw dataset

- cleaned_netflix.csv → Cleaned dataset

- Netflix.ipynb→ Python code

🎯 Conclusion

The dataset was successfully cleaned and prepared for further analysis and visualization
