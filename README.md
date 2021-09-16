### README

#### Peer-graded Assignment: Getting and Cleaning Data Course Project

This repository is a **Olayinka** submission for Getting and Cleaning Data course project. It has the instructions on how to run analysis on Human Activity recognition dataset.

## Project Description
The purpose of this project is to demonstrate the ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis.
In more details, the following steps are required to complete the assignment: 1) a tidy data set as described below; 2) a link to a Github repository with your script for performing the analysis; 3) a Code book that describes the variables, the data, and any transformations performed to clean up the data called.

### Data Description:
The data considered for the Project represent data collected from the accelerometers from the Samsung Galaxy S smartphone.

A full description is available at the web site where the data was obtained: http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones.

The whole data package can be downloaded at the following link: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

#### Files

* `CodeBook.md` a code book that describes the variables, the data, and any transformations or work that I performed to clean up the data

* `run_analysis.R` performs the data preparation and then followed by the 5 steps required as described in the course project's definition:
    + Merges the training and the test sets to create one data set.
    + Extracts only the measurements on the mean and standard deviation for each measurement.
    + Uses descriptive activity names to name the activities in the data set
    + Appropriately labels the data set with descriptive variable names.
    + From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
    
* `FinalData.txt` is the exported final data after going through all the sequences described above.
