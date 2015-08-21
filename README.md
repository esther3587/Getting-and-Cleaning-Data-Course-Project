## Getting-and-Cleaning-Data-Course-Project

####In this project, I took data from this following link: https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip 
,which contains data collected from the accelerometers from the Samsung Galaxy S smartphone.

In the **UCI HAR Dataset** folder, there are two sets of data: train set and test set.
* First I combine the accelerometer data , person ID, and the activity label for each observable into one data set using *cbind()*.
* Then I merge the train set and the test set to create one new data set using *rbind()* and call it ActivityData.
* I rename the column names with descriptions from features.txt and also the **Activity** and **ID** columns.
* I use *grep()* to extract column numbers with only the measurments on the mean and standard deviation for each measurement, and make a new table **TidayData** with only those columns.
* 

Uses descriptive activity names to name the activities in the data set

From the data set in step 4, creates a second, independent tidy data set with the average of each variable for each activity and each subject.
