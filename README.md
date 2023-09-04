# README

## Data Splitting and Export Tool

This Python script is designed to help you split a dataset into three different formats (JSON, CSV, and Database) based on the specified percentages. It is particularly useful when you need to prepare data for various purposes such as machine learning, analysis, or database management.

### Table of Contents
- [Introduction](#introduction)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [License](#license)

---

### Introduction

When working with datasets, it's common to need the data in multiple formats for various tasks. This script provides a convenient way to split a dataset into three parts:

1. **JSON**: This format is suitable for data interchange and is commonly used in web applications and data analysis.
2. **CSV**: Comma-separated values are a standard format for storing tabular data and can be easily imported into spreadsheet software or used in data analysis tools.
3. **Database**: You can insert the data directly into a SQL database for more advanced data management and querying.

### Getting Started

To get started, make sure you have the following prerequisites:

- Python 3.x installed on your system.
- The required Python libraries installed (see [Dependencies](#dependencies)).
- A dataset file in CSV format.

### Usage

1. Clone this repository to your local machine.

   ```shell
   git clone https://github.com/Midofd/Data-Splitter.git
   cd Data-Splitter
   ```

2. Open a terminal and navigate to the project directory.

3. Run the script:

   ```shell
   python data_splitter.py
   ```

4. You will be prompted to enter the percentages for JSON, Database, and CSV splitting.

5. The script will split the dataset according to your specified percentages, export the data to the corresponding formats, and insert the database portion into a SQL database (you need to configure the database connection).

6. The resulting files will be saved in the `exported_dataset` directory, and the database table will be created.

### Dependencies

The script uses the following Python libraries:

- [pandas](https://pandas.pydata.org/): For data manipulation and export.
- [sqlalchemy](https://www.sqlalchemy.org/): For working with databases.
- [math](https://docs.python.org/3/library/math.html): For mathematical calculations.

You can install these libraries using `pip`:

```shell
pip install pandas sqlalchemy
```

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
