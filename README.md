#   Baby Names Analysis with Python

##   Description

This Python project analyzes baby name data provided by the Social Security Administration (SSA) of the United States. It extracts data from zipped files, visualizes birth trends by gender and year, and identifies popular baby names using the Pandas, zipfile, io, and Matplotlib libraries. 

##   Key Features

* **Data Extraction:** Extracts data from multiple year-specific text files within a zipped archive. 
* **Data Visualization:**
    * Visualizes the number of male and female babies born in a particular year. 
    * Visualizes trends in name popularity over time.
    * Visualizes name diversity.
    * Visualizes gender ratio over time.
    * Visualizes the distribution of name popularity.
* **Popular Name Identification:** Determines the most popular baby names overall and for specific years. 
* **Data Manipulation:** Uses Pandas DataFrames for efficient data manipulation and analysis. 

##   Libraries Used

* `pandas`: For data manipulation and analysis. [cite: 9, 4]
* `zipfile`: For working with zipped files. [cite: 9]
* `io`: For handling in-memory file-like objects. [cite: 9, 10]
* `matplotlib`: For data visualization.

##   Setup

1.  **Prerequisites:**
    * Python 3.x
    * (If running locally) Install the required libraries: `pip install pandas zipfile matplotlib`
2.  **Dataset:**
    * Download the dataset from the Social Security Administration (SSA) website:
        * Go to https://www.ssa.gov/oact/babynames/limits.html [cite: 6]
        * Click on 'National data' [cite: 6]
        * Download the zipped file. [cite: 6]
    * Place the zipped file in the project directory.
3.  **Running the Code:**
    * If using Google Colab, upload the zipped file to the Colab environment and run the notebook.
    * If running locally, execute the Python script.

##   Project Structure

├── README.md

├── baby_names_analysis.py  # Main Python script

└── names.zip              # (Downloaded dataset)

##   Usage

The script `baby_names_analysis.py` contains the code to:

* Extract data from the zip file.
* Perform data analysis and calculations.
* Generate visualizations.

The visualizations are displayed within the script's execution (or within the Colab notebook if using Colab).

##   Contributing

Contributions to this project are welcome! Feel free to fork the repository, make changes, and submit pull requests.

##   License

This project is open-source and available under the MIT license.

##   Acknowledgments

* The data used in this project is provided by the Social Security Administration (SSA), United States of America.
