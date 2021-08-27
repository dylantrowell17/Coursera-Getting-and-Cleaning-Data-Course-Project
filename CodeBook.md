## Coursera Getting and Cleaning Data Course Project

## About R script
The R Script `run_analysis.R` prepares the data and then cleans it by performing the following steps as required by the assignment's instructions


## The original data was prepared by

1. Loading dplyr
2. Downloading data set
3. Checking if archive already exists.
4. Checking if folder exists
5. Assigning variable names to all data frames
## The original data was cleaned up by

1. Merging the training and tests data sets to create one data set
2. Extracting only the mean and standard deviation of each measurement 
3. Using descriptive activity names to name each activity in the data set
4. Labeling the data set with descriptive variable names
5. Creating a new, independent tidy data set with the average of each variable for each activity and each subject in TidyData


## About variables:   
* `x_train`, `y_train`, `x_test`, `y_test`, `subject_train` and `subject_test` contain the data from the downloaded files.
* `x_data`, `y_data` and `subject_data` merge the previous datasets to further analysis.
* `features` contains the correct names for the `x_data` dataset, which are applied to the column names stored in
