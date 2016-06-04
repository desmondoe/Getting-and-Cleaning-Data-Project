# Getting-and-Cleaning-Data-Project
Coursera Project
## Overview
This project demonstrate the collection and cleaning of a tidy data set that can be used for subsequent analysis.
A full description of the data used in this project can be found at The UCI Machine Learning Repository.
The purpose of this project is to demonstrate ones ability to collect, work with, and clean a data set. 

The goal is to prepare tidy data that can be used for later analysis. (Grading will be by peers on a series of yes/no question) 
Required to submit: 
- a tidy data set as described below, 
- a link to a Github repository with your script for performing the analysis
- a code book that describes the variables, the data, any transformations or work performed to clean up the data called CodeBook.md. 

### STEPS - Project Summary
- Download the dataset to your working directory
- Load the activity and feature info
- Loads both the training and test datasets, keeping only those columns which reflect a mean or standard deviation
- Loads the activity and subject data for each dataset, and merges those columns with the dataset
- Merges the two datasets
- Converts the activity and subject columns into factors
- Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.

The end result is shown in the file tiddy.txt.

### NOTE: on R script (run_analysis.R) 
### Does the following. 
1. Merges the training and the test sets to create one data set. 
2. Extracts only the measurements on the mean and standard deviation for each measurement. 
3. Uses descriptive activity names to name the activities in the data set 
4. Appropriately labels the data set with descriptive activity names. 
5. Creates a second, independent tidy data set with the average of each variable for each activity and each subject.

### Modifications to This Script

Once you have downloaded and unzipped the source files, you will need to make one modification to the R file before you can process the data. Set the path of the working directory to relect the location of the source files in your own directory.



