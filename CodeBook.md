The files that will be used to load data are  as follows:
1.	test/subject_test.txt
2.	test/X_test.txt
3.	test/y_test.txt
4.	train/subject_train.txt
5.	train/X_train.txt
6.	train/y_train.txt
Values of variables consist following data:
1.	Values of Varible Activity consist of data from “Y_train.txt” and “Y_test.txt”
2.	values of Varible Subject consist of data from “subject_train.txt” and subject_test.txt"
3.	Values of Varibles Features consist of data from “X_train.txt” and “X_test.txt”
4.	Names of Varibles Features come from “features.txt”
5.	levels of Varible Activity come from “activity_labels.txt”
Merges the training and the test sets to create one data set
Data is concatenated;names set to variables, columns merged to get data 
Extracts only the measurements on the mean and standard deviation for each measurement
Data frame is subset by Name of Features by measurements on the mean and standard deviation

Uses descriptive activity names to name the activities in the data set
1.Read descriptive activity names from “activity_labels.txt”	use descriptive activity names for variable acticity 
Appropriately labels the data set with descriptive variable names
, Names of features will labelled using descriptive variable names.
•	prefix t is replaced by time
•	Acc is replaced by Accelerometer
•	Gyro is replaced by Gyroscope
•	prefix f is replaced by frequency
•	Mag is replaced by Magnitude
•	BodyBody is replaced by Body
Creates a second, independent tidy data set and ouput it
independent tidy data set will be created with the average of each variable for each activity 



