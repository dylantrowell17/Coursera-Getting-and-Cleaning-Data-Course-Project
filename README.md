## Coursera Getting and Cleaning Data Course Project
This repository contains the entirety of my submission for the Coursera Getting and Cleaning Data course project. 

## Data set
Human Activity Recognition Using Smartphones
* http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

## Files
* `CodeBook.md` a code book that describes the variables, the data, and any transformations or work that I performed to clean up the data

* `run_analysis.R` is an R scirpt that prepares the data and then cleans it by performing the following steps as required by the assignment's instructions:
  1. Merging the training and tests data sets to create one data set
  2. Extracting only the mean and standard deviation of each measurement 
  3. Using descriptive activity names to name each activity in the data set
  4. Labeling the data set with descriptive variable names
  5. Creating a new, independent tidy data set with the average of each variable for each activity and each subject in TidyData
* `FinalData.txt`t is the final data exported to a .txt file after going through the aforementioned processes.
