# Getting and Cleaning Data Project John Hopkins Coursera

 1. Merges the training and the test sets to create one data set.
 2. Extracts only the measurements on the mean and standard deviation for each measurement.
 3. Uses descriptive activity names to name the activities in the data set
 4. Appropriately labels the data set with descriptive variable names.
 5. From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

# How Code Work

1. Load Packages and get the Data
2. Download Data and put data to working dir
3. Load activity labels + features
4. Load train datasets
5. Load test datasets
6. merge datasets
7. Convert classLabels to activityName basically
8. Export data
