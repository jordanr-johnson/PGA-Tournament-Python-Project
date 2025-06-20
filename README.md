# PGA Tournament Data Cleaning and Exploratory Data Analysis (EDA) Project

## Overview
This project involves cleaning and analyzing a comprehensive dataset of PGA Tour tournament data (`ASA All PGA Raw Data.csv`) to uncover insights into player performance across tournaments and courses. The dataset includes player statistics, tournament details, strokes gained metrics (e.g., `sg_total`, `sg_putt`, `sg_app`), and fantasy points. The project demonstrates data cleaning techniques to handle missing values, inconsistent formats, and non-numeric data, followed by exploratory data analysis (EDA) to identify top performers, course difficulty, and performance trends.

Key focuses include:
- **Data Cleaning**: Handling missing values, standardizing non-numeric `Finish` values (e.g., `T32`, `CUT`, `NA`), removing duplicate values, and ensuring data consistency.
- **EDA**: Analyzing player performance through strokes gained metrics, finish positions, and course-specific trends.
- **Course-Specific Performance**: Identifying top players on specific courses based on average `sg_total`.

This project showcases proficiency in Python, pandas, NumPy, Matplotlib, and Seaborn.

## Dataset
The dataset (`ASA All PGA Raw Data.csv`) contains tournament-level PGA Tour data with 37 columns, including:
- Player and tournament information (`player`, `tournament name`, `course`, `date`, `season`).
- Performance metrics (`strokes`, `hole_par`, `finish_position`).
- Strokes gained metrics (`sg_putt`, `sg_arg`, `sg_app`, `sg_ott`, `sg_t2g`, `sg_total`).
- Fantasy points (`total_DKP`, `total_FDP`, `total_SDP`).

## Project Structure
- `PGA_EDA.ipynb`: Jupyter Notebook containing the full data cleaning and EDA workflow.
- `ASA ALL PGA Raw Data - Tourn Level.csv` original csv data file downloaded from Kaggle.
- `cleaned_pga_data.csv`: Cleaned dataset (output of cleaning steps).

## Requirements
To run the project, install the required Python libraries:
```bash
pip install pandas numpy matplotlib seaborn```

Download the required csv files:
Original for full cleaning and EDA experience
Cleaned for a simple EDA

Instructions are included in the Jupyter Notebook file to follow along with if you so choose. 
