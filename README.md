# Data Cleaning for Gobiz & Grab Merchant Data

## Overview

This Jupyter notebook is designed for data cleaning and preprocessing the menu performance data from GoBiz and Grab Merchant invoices. 

## Features

- **Remove Unnecessary Words:** Cleansing the dataset of superfluous words that add noise rather than value to the analysis.
- **Replace Misspelled Words:** Correcting common spelling errors to ensure consistency and accuracy in the data. For instance, correcting "chiken" to "chicken" in menu item descriptions.
- **Date Formatting:** Standardizing date formats across the dataset to facilitate time series analysis and reporting.
- **Remove Unnecessary Columns:** Identifying and eliminating columns that do not contribute to the analysis objectives, such as redundant information or irrelevant details, to streamline the dataset.
  

## Setup

To run this notebook, you will need to have Python installed on your system, along with Jupyter Notebook or JupyterLab. The analysis relies on several Python libraries, including pandas, numpy, and matplotlib.

### Dependencies

- Python (>=3.7)
- pandas
- numpy
- matplotlib

### Installation

1. **Check Python Installation:**
   - Verify Python installation by running `python --version` in your terminal or command prompt. If Python is not installed, download it from [python.org](https://www.python.org/downloads/).

2. **Install Jupyter:**
   - Install Jupyter Notebook by running the command `pip install notebook`.

3. **Prepare the Environment:**
   - Clone this repository or download the notebook to your local machine.

4. **Navigate to Your Notebook:**
   - Open your terminal or command prompt and navigate to the directory containing the notebook.

5. **Start Jupyter Notebook or JupyterLab:**
   - Run the command `jupyter notebook` or `jupyter lab`, depending on which application you're using.

6. **Open the Notebook:**
   - Navigate to the notebook file in the Jupyter interface and open it to start your data cleaning process.
