## READ_ME.md
#author Natalya Sinitsyna
# getting_and_cleaning_data
#project of getting and cleaning data class on Coursera

This repo contains project code for Getting and Cleaning Data course given by John Hopkins university on Coursera.

Script

The script run_analysis.R contains comands that performs the actual job:
1.download and unzip data from Samsung  
2.reads train and test data sets and merges them
3.processes the merged data set (extract the relevant variables, adds descriptive activity names, etc.)
4.generates the tidy data set
5.writes the merged data set to rawdata.csv
6.writes the tidy data set to tidydata.txt

Library 
1.library(base)
2.library(utils)
3.library(data.table)
