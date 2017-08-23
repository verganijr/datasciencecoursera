# Getting and Cleaning Data

## Course Project

You should create one R script called run_analysis.R that does the following.
1.	Merges the training and the test sets to create one data set.
2.	Extracts only the measurements on the mean and standard deviation for each measurement.
3.	Uses descriptive activity names to name the activities in the data set
4.	Appropriately labels the data set with descriptive activity names.
5.	Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Steps to work on this course project

1.	Download the data source and put into “C:\Data Science” folder on your local drive. You'll have a UCI HAR Dataset folder.
2.	Put run_analysis.R in “C:\Data Science”  folder.
3.	Run source("C:/Data Science/run_analysis.R"), then it will generate a new file tiny_data.txt in “C:\Data Science\UCI HAR Dataset” directory.

## Dependencies

run_analysis.R file will help you to install the dependencies automatically. It depends on reshape2 and data.table.

## Variables

- activity_labels: receives the content of activity_labels.txt file
- features: receives the content of features.txt file
- extract_features: extract mean/std features
- x_test: receives the content of X_test.txt file
- y_test: receives the contexnt of y_test.txt file
- subject_test: receives the content of subject_test.txt file
- test_data: receives the bind of x_test and y_test data
- x_train: receives the content of X_train.txt file
- y_train: receives the contexnt of y_train.txt file
- subject_test: receives the content of subject_train.txt file
- train_data: receives the bind of x_train and y_train data
- data: receives the merge of test and train data
- tidy_data: receives the tidy data set with the average of each variable for each activity and each subject.



