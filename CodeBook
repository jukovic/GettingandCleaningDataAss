## Peer-graded Assignment: Getting and Cleaning Data Course Project Submission

This script will check if the data file is present in your working directory. (If not, will download and unzip the file)

**1. Assign each data to variables**

* subject_test : subject IDs for test

* subject_train : subject IDs for train

* X_test : values of variables in test

* X_train : values of variables in train

* y_test : activity ID in test

* y_train : activity ID in train
 
* activities : Description of activity IDs in y_test and y_train

* features : description(label) of each variables in X_test and X_train

**2. Merge the training and the test sets to create one data set**

* X is created by merging x_train and x_test using rbind() function
* Y is created by merging y_train and y_test using rbind() function
* Subject is created by merging subject_train and subject_test using rbind() function
* MergedData is created by merging Subject, Y and X using cbind() function

**4. Extract only the measurements on the mean and standard deviation for each measurement**

* TidyData is created by subsetting MergedData, selecting only columns: subject, code and the measurements on the mean and standard deviation (std) for each measurement

**5. Uses descriptive activity names to name the activities in the data set**

* Entire numbers in code column of the TidyData replaced with corresponding activity taken from second column of the activities variable

**6. Appropriately label the data set with descriptive variable names **

* code column in TidyData renamed into activities
* All Acc in column’s name replaced by Accelerometer
* All Gyro in column’s name replaced by Gyroscope
* All BodyBody in column’s name replaced by Body
* All Mag in column’s name replaced by Magnitude
* All start with character f in column’s name replaced by Frequency
* All start with character t in column’s name replaced by Time

**7.From the data set in step 4, create a second, independent tidy data set with the average of each variable for each activity and each subject**

* FinalDataIndependent is created by summarizing TidyData, taking the means of each variable for each activity and each subject, after groupped by subject and activity.
* Export FinalDataIndependent into FinalDataIndependent.txt file.
