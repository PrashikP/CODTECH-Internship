# Task 1 – Data Pipeline (ETL)

This project is part of my CODTECH Internship.

## Goal
Automate ETL (Extract → Transform → Load) using Pandas + Scikit-learn.

## Features
- Handles missing values (numeric → median, categorical → most frequent)
- Removes duplicates
- Scales numeric columns
- Encodes categorical columns
- Saves:
  - Human-friendly CSV (`processed_data_human.csv`)
  - Machine-ready CSV (`processed_data_machine.csv`)
  - Preprocessor pipeline (`preprocessor.joblib`)

## Run
Open `task1_etl.ipynb` in Google Colab and run all cells.
Outputs will appear in `/outputs` folder.
