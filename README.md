# Day 16: Load a CSV Dataset

## Objective
Learn how to import real-world tabular data for machine learning workflows using Python and Pandas.

## Description
This project demonstrates the fundamental first step in any data science or machine learning workflow: loading data. By using the Pandas library, this script loads a CSV file into a DataFrame and displays the first and last few records to verify the data was imported correctly.

## Dataset
- **Name:** Iris Dataset (`iris_dataset.csv`)
- **Description:** A classic machine learning dataset containing sepal and petal measurements for three different species of iris flowers.

## Tools Used
- Python
- Pandas
- Jupyter Notebook

## How to Run
1. Ensure you have Python installed on your system.
2. Install the Pandas library if you haven't already:
   ```bash
   pip install pandas
   ```
3. Place the `iris_dataset.csv` file in the same directory as your Jupyter Notebook or Python script.
4. Run the code cells to load the dataset. The script will use `df.head()` to show the first 5 rows and `df.tail()` to show the last 5 rows.

---

## Interview Questions & Answers

**1. What is a CSV file?**
A CSV (Comma-Separated Values) file is a plain text file that stores tabular data (numbers and text). Each line of the file represents a data record, and each record consists of one or more fields separated by commas. It is a universally supported format used to exchange data between different applications, databases, and systems.

**2. How do you load a CSV file using Pandas?**
You can load a CSV file in Pandas using the built-in `pd.read_csv()` function. You simply pass the file path (or a URL) as an argument to this function. 
*Example:* `df = pd.read_csv('filename.csv')`. This function automatically reads the text file and parses the tabular data into a Pandas DataFrame.

**3. What is a DataFrame?**
A DataFrame is a two-dimensional, size-mutable, and potentially heterogeneous tabular data structure in Pandas. You can think of it as a programmatic version of a spreadsheet or a SQL table, consisting of rows and columns. It is the primary data structure used in Pandas for data manipulation, analysis, and cleaning.
