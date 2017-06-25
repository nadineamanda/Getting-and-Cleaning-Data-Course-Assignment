## Source Data Used for this Assignment

All data used for this project was taken from the Human Activity Recognition Using Smartphones Data Set

A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

## About the R Script

The R script for this assignment covers the following steps.

Step 1: Merging the training and the test sets to create one data set.


Step 2: Extracting only the measurements on the mean and standard deviation for each measurement


Step 3: Uses descriptive activity names to name the activities in the data set


Step 4: Appropriately labels the data set with descriptive variable names.


Step 5: From the data set in step 4, creates a second,
independent tidy data set with the average of each variable for each activity and each subject.

## Variables Used in this Data Set

features contains the correct names for the x_data dataset


x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the Human Activity Recognition Using Smartphones Data Set.


x_data, y_data and subject_data merge both of the data sets.

## Columns in output file

Here are the columns included in the output file:

subject_id - The id of the participant.

activity_labels - The name of the activity that the measurements correspond to
