#Data codebook

##Files in folder ‘UCI HAR Dataset’ that will be used are:

1.SUBJECT FILES

          test/subject_test.txt

          train/subject_train.txt

2.ACTIVITY FILES

          test/X_test.txt

          train/X_train.txt

3.DATA FILES

          test/y_test.txt

          train/y_train.txt

4.features.txt - Names of column variables in the dataTable


5.activity_labels.txt - Links the class labels with their activity name.


##Following steps/transformations have been applied to the dataset.

1.Merges the training and the test sets to create one data set.

2.Extracts only the measurements on the mean and standard deviation for each measurement.

3.Uses descriptive activity names to name the activities in the data set

4.Appropriately labels the data set with descriptive variable names.

5.creates a second, independent tidy data set with the average of each variable for each activity and each subject.

The script to perform the above actions can be found on the following link.

https://github.com/samkamiru/Getting-and-Cleaning-Data/blob/master/run_analysis.R

##Achieving the results

Load test and train data

load data labels .i.e. features and activity

Extract the mean and STDev columns name and data.

Merge the datasets 

Output the dataset in a tab delimited text file and named tidy_data.txt
