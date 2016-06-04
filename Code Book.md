###Summary of Data Set Information
The experiments of a group of 30 volunteers within an age bracket of 19-48 years. Each person performed six activities
(WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist.

###What was captured using its embedded accelerometer and gyroscope (smartphone)
 * 3-axial linear acceleration 
 * 3-axial angular velocity  
 Dataset obtained was partitioned into two sets: 70% for training data and 30% for the test data.
 
###Attribute Information
1. Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration.
2. Triaxial Angular velocity from the gyroscope.
3. A 561-feature vector with time and frequency domain variables.
4. Its activity label.
5. An identifier of the subject who carried out the experiment.

###Identifiers
Subject - The ID of the test subject
Activity - Type of activity performed while measurements were taken
Measurement - what was measured - MEAN AND STANDARD DEVIATION: 3-axial linear acceleration, 3-axial angular velocity.

###Activity Labels (DATA SET INFORMATION)
1.WALKING (value 1): subject was walking during the test
2.WALKING_UPSTAIRS (value 2): subject was walking up a staircase during the test
3.WALKING_DOWNSTAIRS (value 3): subject was walking down a staircase during the test
4.SITTING (value 4): subject was sitting during the test
5.STANDING (value 5): subject was standing during the test
6.LAYING (value 6): subject was laying down during the test

###STEP ONE (MERGE):  Training + Test Sets =  Data set.
After setting the source directory for the files, read into tables the data located in the following
y_train.txt
subject_test.txt
x_test.txt
y_test.txt
features.txt
activity_labels.txt
subject_train.txt
x_train.txt

Assign column names and merge to create one data set.

