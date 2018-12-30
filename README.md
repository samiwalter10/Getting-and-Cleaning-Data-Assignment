# Getting-and-Cleaning-Data-Assignment

This is the programming assignment for the Getting and Cleaning Data Coursera course week 4. 
The R script, run_analysis.R, does the following:

1. Downloads the dataset if it does not already exist in the working directory
2. Loads both the trianing and test datasets and loads the activity and feature info
3. Merges the training and test data sets
4. Keeps only the measurements on the mean and standard deviation for each measurement
5. Renames data with more descriptive names and cleans up column titles
6. Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

The end result is shown in the file tidy.txt.
