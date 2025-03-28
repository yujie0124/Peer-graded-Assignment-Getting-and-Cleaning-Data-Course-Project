#Code Book

This is the code book for tidy data set.

### The original data was transformed by

-Merging the training and the test sets to create one data set.

-Extracting only the measurements on the mean and standard deviation for each measurement.

-Using descriptive activity names to name the activities in the data set

-Appropriately labeling the data set with descriptive activity names.

-Creating a second, independent tidy data set with the average of each variable for each activity and each subject.

### About variables:
-x_train, y_train, x_test, y_test, subject_train and subject_test contain the data from the downloaded files.

-x_data, y_data and subject_data merge the previous datasets to further analysis.

-features contains the correct names for the x_data dataset, which are applied to the column names stored in

-Names used:

"subject" "activity" "timeBodyAccelerometer-mean()-X" "timeBodyAccelerometer-mean()-Y" "timeBodyAccelerometer-mean()-Z" "timeBodyAccelerometer-std()-X" "timeBodyAccelerometer-std()-Y" "timeBodyAccelerometer-std()-Z" "timeGravityAccelerometer-mean()-X" "timeGravityAccelerometer-mean()-Y" "timeGravityAccelerometer-mean()-Z" "timeGravityAccelerometer-std()-X" "timeGravityAccelerometer-std()-Y" "timeGravityAccelerometer-std()-Z" "timeBodyAccelerometerJerk-mean()-X" "timeBodyAccelerometerJerk-mean()-Y" "timeBodyAccelerometerJerk-mean()-Z" "timeBodyAccelerometerJerk-std()-X" "timeBodyAccelerometerJerk-std()-Y" "timeBodyAccelerometerJerk-std()-Z" "timeBodyGyroscope-mean()-X" "timeBodyGyroscope-mean()-Y" "timeBodyGyroscope-mean()-Z" "timeBodyGyroscope-std()-X" "timeBodyGyroscope-std()-Y" "timeBodyGyroscope-std()-Z" "timeBodyGyroscopeJerk-mean()-X" "timeBodyGyroscopeJerk-mean()-Y" "timeBodyGyroscopeJerk-mean()-Z" "timeBodyGyroscopeJerk-std()-X" "timeBodyGyroscopeJerk-std()-Y" "timeBodyGyroscopeJerk-std()-Z" "timeBodyAccelerometerMagnitude-mean()" "timeBodyAccelerometerMagnitude-std()" "timeGravityAccelerometerMagnitude-mean()" "timeGravityAccelerometerMagnitude-std()" "timeBodyAccelerometerJerkMagnitude-mean()" "timeBodyAccelerometerJerkMagnitude-std()" "timeBodyGyroscopeMagnitude-mean()" "timeBodyGyroscopeMagnitude-std()" "timeBodyGyroscopeJerkMagnitude-mean()" "timeBodyGyroscopeJerkMagnitude-std()" "frequencyBodyAccelerometer-mean()-X" "frequencyBodyAccelerometer-mean()-Y" "frequencyBodyAccelerometer-mean()-Z" "frequencyBodyAccelerometer-std()-X" "frequencyBodyAccelerometer-std()-Y" "frequencyBodyAccelerometer-std()-Z" "frequencyBodyAccelerometerJerk-mean()-X" "frequencyBodyAccelerometerJerk-mean()-Y" "frequencyBodyAccelerometerJerk-mean()-Z" "frequencyBodyAccelerometerJerk-std()-X" "frequencyBodyAccelerometerJerk-std()-Y" "frequencyBodyAccelerometerJerk-std()-Z" "frequencyBodyGyroscope-mean()-X" "frequencyBodyGyroscope-mean()-Y" "frequencyBodyGyroscope-mean()-Z" "frequencyBodyGyroscope-std()-X" "frequencyBodyGyroscope-std()-Y" "frequencyBodyGyroscope-std()-Z" "frequencyBodyAccelerometerMagnitude-mean()" "frequencyBodyAccelerometerMagnitude-std()" "frequencyBodyAccelerometerJerkMagnitude-mean()" "frequencyBodyAccelerometerJerkMagnitude-std()" "frequencyBodyGyroscopeMagnitude-mean()" "frequencyBodyGyroscopeMagnitude-std()" "frequencyBodyGyroscopeJerkMagnitude-mean()" "frequencyBodyGyroscopeJerkMagnitude-std()"