Getting-and-Cleaning-Data
=========================

Course Project: run_analysis.R

function download.data():
The function downloads the Samsung data and extracts it.

function load.dataset():
The function loads and processes either a train or a test data set, given that current directory is the Samsung data set.

function run.analysis():
Merges the training and the test sets to create one data set.
Extracts only the measurements on the mean and standard deviation for each measurement. 
Uses descriptive activity names to name the activities in the data set.
Appropriately labels the data set with descriptive activity names. 
Creates a second, independent tidy data set with the average of each variable for each activity and each subject and returns it.
Creates tidydata.csv file.


Source run_analysis.R file to R-console / R-Studio. 
Download the data using download.data() function, by setting the appropriate directories (working directory etc.)
execute the function run.analysis(), to get the result.