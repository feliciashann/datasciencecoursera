## Overview

This is the final project for getting and cleaning data course final project from ¡§Launch Your Career in Data Science¡¨ by Johns Hopkins U.
The purpose of this project is to demonstrate your ability to collect, work with, and clean a data set. The goal is to prepare tidy data that can be used for later analysis. 

Main goal of this project includes:

1. Merges the training and the test sets to create one data set.
2. Extracts only the measurements on the mean and standard deviation for each measurement.
3. Uses descriptive activity names to name the activities in the data set
4. Appropriately labels the data set with descriptive variable names.
5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

## Introduction

In run_analysis.R, datasets are downloaded if its not found in working directory as a folder named "UCI HAR Dataset".

After downloading, 1st task is done by performing Rbind.

2nd task is done by text processing through techniques introduced in regular expression & text processing chapter.

3rd task is done by renaming the data.activity.labels and another merge. 

4th task can be done either by original R function or dplyr function; former one is adopted in this case.

finally, using cbind to create & write out the tidy data set.