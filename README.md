##Coursera
###Project for "Getting and Cleaning Data"

* Read in dataframes Xtrain (7352 obs) and Xtest (2947 obs). Combine them to form Xcombo (10299 x 561)
* Get the column names in Xcombo from the file features.txt
* Use "grepl" to extract (from features) only variable involving a mean or standard deviation
* Selecting only these columns, create the smaller dataframe XMeansStds

### Subject and Activity (Dependent) variables

* Get subject & activity from the given text files. Replace the value in the activity variable with the labels.
* cbind the subject, activity, and XMeansStds dataframes.
* Create the NEW variable subjXact for all combinations of subject (30) and activity (6)
* Finally, use tapply to get the 35 x 79 matrix , Xnew, and write it to Xnew.txt
