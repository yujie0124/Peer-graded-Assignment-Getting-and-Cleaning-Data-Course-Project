# Peer-graded-Assignment-Getting-and-Cleaning-Data-Course-Project

### Introduction
This is the peer graded assignment for Cousera Getting and Cleaning Data Course Project

###Data Source
The data linked to from the course website represent data collected from the accelerometers from the Samsung Galaxy S smartphone. A full description is available at the site where the data was obtained:

http://archive.ics.uci.edu/ml/datasets/Human+Activity+Recognition+Using+Smartphones

Here are the data for the project:

https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip

###Run Analysis File Description
The run_analysis.R can be run as long as setting your working directory to the UCI HAR Dataset folder. 

Analysis will read all the test data and train data and merges the training and the test sets to create one data set. Each variables were names accordingly based on the features listed in the features.txt file.

Using the combined data set,independent tidy data set with the average of each variable for each activity and each subject were created and written into tidydata.txt file.
