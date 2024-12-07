# Data_cleaning-in-PANDAS
# Customer Call List Data Cleaning with Pandas

This project demonstrates the cleaning of a customer call list dataset using Python's Pandas library. The main objective was to ensure data accuracy by removing duplicates, trimming unnecessary whitespace, replacing unwanted characters, and standardizing the dataset.
Key functions utilized include `drop_duplicates` for removing duplicate entries, `str.strip()` for eliminating leading and trailing whitespace, and `str.replace()` for replacing specific characters or substrings with desired values. Custom transformations were applied using `lambda` functions, enabling operations like converting text to lowercase or performing column-specific formatting. In some cases, methods were combined (e.g., `str.strip().str.replace()`) to execute multiple cleaning steps simultaneously. 

The project workflow began with loading the raw dataset using Pandas, followed by applying these cleaning techniques systematically to achieve a well-structured and reliable dataset. Once cleaned, the data was saved into a new file for further use. The repository is structured with separate directories for raw data (`data`), Python scripts (`scripts`), and the cleaned output. Users can run the cleaning script by navigating to the `scripts` folder and executing `data_cleaning.py`. 
