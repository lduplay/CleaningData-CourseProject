### Getting and Cleaning Data Course Project

One of the most exciting areas in all of data science right now is wearable computing. Companies like Fitbit, Nike, and Jawbone Up are racing to develop the most advanced algorithms to attract new users. The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available [here](http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones).

The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis.   

The files used in this project can be download by following this [link](https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip). The scripts in this repo assumes these files (in the `UCI HAR Dataset` folder) are located in your working directory.

Use `source(run_analysis.R)` to run the script. The code will do the following actions

1. Merges the training and the test sets to create one data set. 
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set 
4. Appropriately labels the data set with descriptive variable names.  
5. From the data set `tidy` in step 4, creates a second, independent tidy data set `tidy_average` with the average of each variable for each activity and each subject, and saves it to `tidy_data.txt`.

For more information on the resulting datasets, please consult CODEBOOK.md.