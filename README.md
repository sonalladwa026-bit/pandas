# IPL Match Analysis Notebook

This repository contains a Jupyter Notebook (`.ipynb`) dedicated to loading, inspecting, and cleaning an Indian Premier League (IPL) matches dataset[cite: 3].

## Project Overview

The primary goal of this notebook is to demonstrate essential Data Cleaning and Exploratory Data Analysis (EDA) techniques using **Pandas** in Python[cite: 3]. The notebook imports raw match data spanning from the 2007/08 season up to the 2024 season[cite: 3].

## Key Steps & Workflow

1. **Environment Setup & Data Loading:**
   * Package installation (`pandas`)[cite: 3].
   * Importing data from `matches.csv` into a Pandas DataFrame[cite: 3].

2. **Data Inspection:**
   * Viewing initial and final records (`head()`, `tail()`)[cite: 3].
   * Checking DataFrame dimensions (`shape`), length (`len()`), and structure (`columns`, `info()`)[cite: 3].
   * Inspecting statistical summaries (`describe()`) and specific rows (`iloc`)[cite: 3].

3. **Data Cleaning:**
   * Checking for duplicate records (`duplicated().sum()`)[cite: 3].
   * Handling missing values (`isnull().sum()`)[cite: 3].
   * Dropping sparse or unnecessary columns (e.g., removing the `method` column)[cite: 3].
   * Removing missing values (`dropna()`) to prepare a clean dataset for analysis[cite: 3].

## Dataset Summary

* **Initial Dataset Size:** 1,095 rows, 20 columns[cite: 3].
* **Cleaned Dataset Size:** 1,028 rows, 19 columns[cite: 3].
* **Key Features:** `id`, `season`, `city`, `date`, `match_type`, `player_of_match`, `venue`, `team1`, `team2`, `toss_winner`, `toss_decision`, `winner`, `result`, `result_margin`, `target_runs`, `target_overs`, `super_over`, `umpire1`, `umpire2`[cite: 3].

## Requirements

To run this notebook, ensure you have the following installed:

* **Python 3.x**
* **Jupyter Notebook** or **JupyterLab**
* **Pandas**

```bash
pip install pandas
