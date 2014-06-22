Introduction
============

This repository hosts the neccessary files required for the peer project in the Coursera Data Science Course: Getting And Cleaning Data.

The purpose of this project is to demonstrate how to collect, work with, and clean a data set. As a result, a tidy data set has been created to be used for later analysis.




About The Data Set:

The data set: "Human Activity Recognition Using Smartphones" was obtained from UCI:
        https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip
For further information on the dataset:
        http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones




About the files and R script:

The Data Set is located in the directory/folder: UCI HAR Dataset/ .

The CodeBook.md describes the variables, the data, and the work that has been performed to clean up the data.
**  Please review the file: CodeBook.md   for details on how all the scripts work and how they are connected.




**  HOW TO EXECUTE THE SCRIPT  **:

The file to execute is a R.script called:  run_analysis.R  .
It can be loaded into R/Rstudio and executed without any parameters.

The script will auto download the UCI data and auto unzip it and then read into the R environment.  Note: This process may take some time depending on the speed of your internet connection.

The result of the execution is that a tidy.csv file will be created.  The file stores the data (mean and standard deviation of each measurement per activity and subject) for later analysis.




        ** Important Information.


