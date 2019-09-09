# course-project-for-Coursera-Getting-and-Cleaning-Data
This is the third course project for the Getting and Cleaning Data Coursera. The R script, run_analysis.R, does the following:
1.Download the dataset and create a new directory if it does not already exist in the working directory.
2.Get the activity and feature info.
3.Merge both the training and test datasets and only leave those columns which contaisn a mean or standard deviation.
4.Loads the activity and subject data for each dataset, and merges those columns with the dataset.
5.Converts the activity and subject columns into factor.
6.Creates a tidy dataset that consists of the average (mean) value of each variable for each subject and activity pair.
The end result is shown in the file MeanData.txt.





