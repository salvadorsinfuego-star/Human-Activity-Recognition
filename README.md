# Getting and Cleaning Data Course Project

## Overview

This project demonstrates how to collect, clean, and summarize data from the UCI Human Activity Recognition Using Smartphones dataset.

## Files

- run_analysis.R: Script used to download, merge, clean, and summarize the data.
- CodeBook.md: Describes the variables and data transformations.
- tidy_data.txt: Final tidy dataset containing average measurements for each subject and activity.
- tidy_data_all_measurements.txt: Combined dataset before averaging.

## How to Run

1. Open RStudio.
2. Open run_analysis.R.
3. Run the complete script.
4. The script downloads and processes the dataset.
5. The final tidy dataset is saved as tidy_data.txt.

## Data Source

UCI Human Activity Recognition Using Smartphones dataset.

https://archive.ics.uci.edu/dataset/240/human+activity+recognition+using+smartphones

## Output

The final dataset contains 180 rows and 68 columns. Each row represents one subject and one activity, with average values for the selected measurements.
