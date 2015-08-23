### Data Cleansing script

#### Input Dataset: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 

#### Dataset includes the following:
- 'README.txt'
- 'features_info.txt': Shows information about the variables used on the feature vector.
- 'features.txt': List of all features.
- 'activity_labels.txt': Links the class labels with their activity name.
- 'train/X_train.txt': Training set.
- 'train/y_train.txt': Training labels.
- 'test/X_test.txt': Test set.
- 'test/y_test.txt': Test labels. 

#### Data Clean: run_analysis.R script does the following: 
1.	Merges the training and the test sets to create one data set.
2.	Extracts only the measurements on the mean and standard deviation for each measurement. 
3.	Uses descriptive activity names to name the activities in the data set
4.	Labels the data set with descriptive variable names. 
5.	From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.

#### Output Data: tidydata.txt
