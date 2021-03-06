### Getting and Cleaning Data Course Project

## Overview 
Getting and Cleaning Data Course Project demonstrate the ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. The R scripts does the following. 
1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names. 
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

The data for the project: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

Addition: 
The script downloads the dataset if it doesn't exist.

## Files

CodeBook.md describes the variables, the data, and any transformations or work that was performed to clean up the data.

README.md is project description 

run_analyis.R contains R script and performs above required task. 

Average_data.txt output file of  the tidy dataset with the average of variable as requred in step 5


## How to run run_analyisi.R

* Run/ Source the R script from the R prompt or Rstudio.
* Scripts check's if the file exits or not
* Performs all the above steps in project description and output the average_data.txt
