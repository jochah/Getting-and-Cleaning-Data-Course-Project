# Getting-and-Cleaning-Data-Course-Project
Repository to answer the Getting and Cleaning Data Course Project
This documets describes how the script works and the files contained in the repository

1) Files:
- README: It is this file
- CodeBook: Describes the variables
- run_analysis.R: The R script requested for the project
- FinalData.txt: The tidy data obtained after step 5

2) Hot the script works

- It downloads the file and unzip it in UCI HAR Dataset
- Creates dataframes from each txt file contained in UCI HAR Dataset
- Merges the training and the test set to create one data set
- Extracts only the measurements on the mean and standard deviation for each measurement
- Uses descriptive activity names to name the activities in the data set
- Appropriately labels the data set with descriptive variable names
- From the data set in previous step, creates a second, independent tidy data set with the average of each variable for each activity and each subject.


