#Getting Data Project

#Description
This data set is the tidy data set created after the refinement and merging of different data

#Information
The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. Each person performed
six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) 
wearing a smartphone (Samsung Galaxy S II) on the waist. Using its embedded accelerometer and gyroscope,
we captured 3-axial linear acceleration and 3-axial angular velocity at a constant rate of 50Hz.
The experiments have been video-recorded to label the data manually. The obtained dataset has been randomly partitioned into
two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data.

#Variables
tBodyAccMeanX  <br />
tBodyAccMeanY<br />
tBodyAccMeanZ<br />
tBodyAccStdX<br />
tBodyAccStdY<br />
tBodyAccStdZ<br />
tGravityAccMeanX<br />
tGravityAccMeanY<br />
tGravityAccMeanZ<br />
tGravityAccStdX<br />
tGravityAccStdY<br />
tGravityAccStdZ<br />
tBodyAccJerkMeanX<br />
tBodyAccJerkMeanY<br />
tBodyAccJerkMeanZ<br />
tBodyAccJerkStdX<br />
tBodyAccJerkStdY<br />
tBodyAccJerkStdZ<br />
tBodyGyroMeanX<br />
tBodyGyroMeanY<br />
tBodyGyroMeanZ<br />
tBodyGyroStdX<br />
tBodyGyroStdY<br />
tBodyGyroStdZ<br />
tBodyGyroJerkMeanX<br />
tBodyGyroJerkMeanY<br />
tBodyGyroJerkMeanZ<br />
tBodyGyroJerkStdX<br />
tBodyGyroJerkStdY<br />
tBodyGyroJerkStdZ<br />
tBodyAccMagMean<br />
tBodyAccMagStd<br />
tGravityAccMagMean<br />
tGravityAccMagStd<br />
tBodyAccJerkMagMean<br />
tBodyAccJerkMagStd<br />
tBodyGyroMagMean<br />
tBodyGyroMagStd<br />
tBodyGyroJerkMagMean<br />
tBodyGyroJerkMagStd<br />
fBodyAccMeanX<br />
fBodyAccMeanY<br />
fBodyAccMeanZ<br />
fBodyAccStdX<br />
fBodyAccStdY<br />
fBodyAccStdZ<br />
fBodyAccMeanFreqX<br />
fBodyAccMeanFreqY<br />
fBodyAccMeanFreqZ<br />
fBodyAccJerkMeanX<br />
fBodyAccJerkMeanY<br />
fBodyAccJerkMeanZ<br />
fBodyAccJerkStdX<br />
fBodyAccJerkStdY<br />
fBodyAccJerkStdZ<br />
fBodyAccJerkMeanFreqX<br />
fBodyAccJerkMeanFreqY<br />
fBodyAccJerkMeanFreqZ<br />
fBodyGyroMeanX<br />
fBodyGyroMeanY<br />
fBodyGyroMeanZ<br />
fBodyGyroStdX<br />
fBodyGyroStdY<br />
fBodyGyroStdZ<br />
fBodyGyroMeanFreqX<br />
fBodyGyroMeanFreqY<br />
fBodyGyroMeanFreqZ<br />
fBodyAccMagMean<br />
fBodyAccMagStd<br />
fBodyAccMagMeanFreq<br />
fBodyBodyAccJerkMagMean<br />
fBodyBodyAccJerkMagStd<br />
fBodyBodyAccJerkMagMeanFreq<br />
fBodyBodyGyroMagMean<br />
fBodyBodyGyroMagStd<br />
fBodyBodyGyroMagMeanFreq<br />
fBodyBodyGyroJerkMagMean<br />
fBodyBodyGyroJerkMagStd<br />
fBodyBodyGyroJerkMagMeanFreq<br />


#files
features.txt<br />
activity_labels.tx<br />t
subject_train.txt<br />
x_train.txt<br />
y_train.txt<br />
subject_test.txt<br />
x_test.txt<br />
y_test.txt<br />

#process of refining data
R code implement the following

* Merges the training and the test sets to create one data set.
* Extracts only the measurements on the mean and standard deviation for each measurement.
* Uses descriptive activity names to name the activities in the data set
* Appropriately labels the data set with descriptive activity names.
* Creates a second, independent tidy data set with the average of each variable for each activity and each subject.
