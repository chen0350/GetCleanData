Peer-graded Assignment: Getting and Cleaning Data Course Project Week 4

This repository is my submission for Getting and Cleaning Data course project. It has the instructions on how to run analysis on Human Activity recognition dataset.

Objective: explains the analysis files in a clear and understandable way

Dataset
A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here is the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

Files

Code Book 10 Jul .Rmd a code book that describes the variables, the data, and any transformations or work performed to clean up the data

run_analysis.R performs the data preparation and then followed by the steps required as described in the course assignment’s definition:
Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement.
Uses descriptive activity names to name the activities in the data set
Appropriately labels the data set with descriptive variable names.
From the data set in step above, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
FinalData.txt is the exported final data after going through all the steps described above.
