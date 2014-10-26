Getting and Cleaning Data
=========================

This is a repository for code written for the Getting and Cleaning Data project .

## Course Project
(find all project-related materials in the UCI HAR Dataset directory, however, copies of the important files have been put into this main directory to fulfill the submission requirement)

* Unzip the source (https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip) into a folder on your local drive, say D:/Coursera/data/UCI HAR Dataset

* Put run_analysis.R into D:/Coursera/data/UCI HAR Dataset

* In RStudio: setwd("D:/Coursera/data/UCI HAR Dataset"), followed by: source("run_analysis.R")

* Use data <- read.table("data_set_with_the_averages.txt") to read the data. It is 180x68 because there are 30 subjects and 6 activities, thus "for each activity and each subject" means 30 * 6 = 180 rows. Note that the provided R script has no assumptions on numbers of records, only on locations of files.
