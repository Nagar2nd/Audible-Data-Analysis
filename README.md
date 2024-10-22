# Audible Data Cleaning Project

## Project Overview
This project focuses on cleaning and standardizing an Audible dataset using Power Query Editor in Excel. 
The dataset was transformed to ensure consistency and prepared for further analysis by applying various data cleaning techniques.

**Dataset Link**: https://drive.google.com/file/d/1yjyozaSrwShoaROq-TDuSgC5HNLLmrTE/view?usp=sharing

## Data Cleaning Tasks
- **Name Standardization:** Converted the "Name" column to consistent title casing for uniformity.
- **Author Name Separation:** Split combined first and last names in the "Author" column where necessary.
- **Release Date Format:** Ensured all entries in the "ReleaseDate" column follow the "DD-MM-YYYY" format.
- **Time Conversion:** Converted the "Time" column from text to a recognized Excel duration format.
- **Price Standardization:** Ensured all entries in the "Price" column are numeric and consistently formatted with two decimal places, identifying and correcting any non-numeric values.
- **Rating Conversion:** Converted text-based star ratings in the "Stars" column to numeric values.
- **Narrator Splitting:** Split the "NarratedBy" column into multiple columns if multiple narrators were listed.
- **Release Info Column:** Merged the "ReleaseDate" and "Language" columns into a new "ReleaseInfo" column in the format "DD-MM-YYYY, Language."

## Key Excel Features Used
- **Power Query Editor:** For column formatting, data splitting, and transformation tasks.
- **Text to Columns:** To separate combined names and narrators.
- **Data Type Conversion:** Converted text data types to appropriate formats like numeric and date.
- **Merge Columns:** Combined "ReleaseDate" and "Language" into a single column using custom formatting.
- **Conditional Formatting:** Applied for visual consistency checks.

## Conclusion
The project effectively cleaned and standardized the Audible dataset, ensuring uniformity in column formats and preparing it for deeper analysis. Power Query Editor's transformation capabilities were pivotal in streamlining this process.




