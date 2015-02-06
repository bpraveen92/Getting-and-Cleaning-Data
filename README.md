Getting and Cleaning Data Course Project
About the Course
Before you can work with data you have to get some. This course will cover the basic ways that data can be obtained. The course will cover obtaining data from the web, from APIs, from databases and from colleagues in various formats. It will also cover the basics of data cleaning and how to make data “tidy”. Tidy data dramatically speed downstream data analysis tasks. The course will also cover the components of a complete data set including raw data, processing instructions, codebooks, and processed data. The course will cover the basics needed for collecting, cleaning, and sharing data.

Course Syllabus
Upon completion of this course you will be able to obtain data from a variety of sources. You will know the principles of tidy data and data sharing. Finally, you will understand and be able to apply the basic tools for data cleaning and manipulation.
This file describes how run_analysis.R script works.

Project Details:

First, unzip the data from https://d396qusza40orc.cloudfront.net/getdata%2Fprojectfiles%2FUCI%20HAR%20Dataset.zip and rename the folder with "data".
Make sure the folder "data" and the run_analysis.R script are both in the current working directory.
Second, use source("run_analysis.R") command in RStudio.
Third, you will find two output files are generated in the current working directory:
merged_data.txt (7.9 Mb): it contains a data frame called cleanedData with 10299*68 dimension.
data_with_means.txt (220 Kb): it contains a data frame called result with 180*68 dimension.
Finally, use data <- read.table("data_with_means.txt") command in RStudio to read the file. Since we are required to get the average of each variable for each activity and each subject, and there are 6 activities in total and 30 subjects in total, we have 180 rows with all combinations for each of the 66 features.
