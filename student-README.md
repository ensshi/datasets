### Student Dropout and Academic Success Analysis

##Overview:
This repository contains a Python script for in-depth analysis of a student dataset ('data.csv'), aiming to predict dropout and academic success. The dataset, sourced from UCI Machine Learning Repository, encompasses various features such as demographics, academic performance, and economic indicators.

##Dependencies:
Make sure you have the following Python libraries installed:

- pandas
- matplotlib
- numpy
- seaborn

You can install them using:

```bash
pip install pandas matplotlib numpy seaborn
```

## Usage:

1. Download the dataset ('data.csv') and place it in the same directory as the script.
2. Run the script to load the data and perform exploratory data analysis.

```python
python analyze_student_data.py
```

## Script Details:

The script utilizes the pandas library for data manipulation and provides insights into the structure and characteristics of the weather dataset, including:
- Displaying the first 5 rows of the dataset.
- Showing the shape of the dataset (8784 rows, 8 columns).
- Listing the column names and data types.
- Displaying the unique values and the number of unique values for the "Weather" column.
- Counting the occurrences of each unique value in the "Weather" column.
- Displaying general information about the dataset using `data.info()`.

The script also includes various data manipulation operations such as filtering, grouping, and renaming columns.
