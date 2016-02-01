#Codebook for Final Project
### Getting and Cleaning Data

jcrawford
2016-01-31


##Description of the dataset
Human Activity Recognition database built from the recordings of 30 subjects performing 
activities of daily living (ADL) while carrying a waist-mounted smartphone with embedded inertial sensors.


##Steps to create tidy dataset
1. Download zip file and extract contents
2. Read in the labels necessary for the data and subset to only vars pertaining to mean and std
3. Read in both the training and test data, merging labels with data
4. Merge the 2 datasets
5. Melt and cast the dataset, averaging all values
6. Write out the new dataset to a text file

## Variables

### Activities
1 WALKING
2 WALKING_UPSTAIRS
3 WALKING_DOWNSTAIRS
4 SITTING
5 STANDING
6 LAYING

### Features
"tBodyAccMeanX"
"tBodyAccMeanY"
"tBodyAccMeanZ"
"tBodyAccStdX"
"tBodyAccStdY"
"tBodyAccStdZ"
"tGravityAccMeanX"
"tGravityAccMeanY"
"tGravityAccMeanZ"
"tGravityAccStdX"
"tGravityAccStdY"
"tGravityAccStdZ"
"tBodyAccJerkMeanX"
"tBodyAccJerkMeanY"
"tBodyAccJerkMeanZ"
"tBodyAccJerkStdX"
"tBodyAccJerkStdY"
"tBodyAccJerkStdZ"
"tBodyGyroMeanX"
"tBodyGyroMeanY"
"tBodyGyroMeanZ"
"tBodyGyroStdX"
"tBodyGyroStdY"
"tBodyGyroStdZ"
"tBodyGyroJerkMeanX"
"tBodyGyroJerkMeanY"
"tBodyGyroJerkMeanZ"
"tBodyGyroJerkStdX"
"tBodyGyroJerkStdY"
"tBodyGyroJerkStdZ"
"tBodyAccMagMean"
"tBodyAccMagStd"
"tGravityAccMagMean"
"tGravityAccMagStd"
"tBodyAccJerkMagMean"
"tBodyAccJerkMagStd"
"tBodyGyroMagMean"
"tBodyGyroMagStd"
"tBodyGyroJerkMagMean"
"tBodyGyroJerkMagStd"
"fBodyAccMeanX"
"fBodyAccMeanY"
"fBodyAccMeanZ"
"fBodyAccStdX"
"fBodyAccStdY"
"fBodyAccStdZ"
"fBodyAccMeanFreqX"
"fBodyAccMeanFreqY"
"fBodyAccMeanFreqZ"
"fBodyAccJerkMeanX"
"fBodyAccJerkMeanY"
"fBodyAccJerkMeanZ"
"fBodyAccJerkStdX"
"fBodyAccJerkStdY"
"fBodyAccJerkStdZ"
"fBodyAccJerkMeanFreqX"
"fBodyAccJerkMeanFreqY"
"fBodyAccJerkMeanFreqZ"
"fBodyGyroMeanX"
"fBodyGyroMeanY"
"fBodyGyroMeanZ"
"fBodyGyroStdX"
"fBodyGyroStdY"
"fBodyGyroStdZ"
"fBodyGyroMeanFreqX"
"fBodyGyroMeanFreqY"
"fBodyGyroMeanFreqZ"
"fBodyAccMagMean"
"fBodyAccMagStd"
"fBodyAccMagMeanFreq"
"fBodyBodyAccJerkMagMean"
"fBodyBodyAccJerkMagStd"
"fBodyBodyAccJerkMagMeanFreq"
"fBodyBodyGyroMagMean"
"fBodyBodyGyroMagStd"
"fBodyBodyGyroMagMeanFreq"
"fBodyBodyGyroJerkMagMean"
"fBodyBodyGyroJerkMagStd"
"fBodyBodyGyroJerkMagMeanFreq"
