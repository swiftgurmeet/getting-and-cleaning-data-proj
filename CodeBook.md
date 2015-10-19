## Code Book for the Course Project

### The data set is contained in the file tidy.txt.

1. The field `subject` denotes the subject that performed an activity represented by a unique number. There are 30 in all.
2. The second field `activity` denotes the activity performed by the subject. There are six types of activites here:

* WALKING
* WALKING_UPSTAIRS
* WALKING_DOWNSTAIRS
* SITTING
* STANDING
* LAYING



3. Rest of the fields are means of the set of data (features) collected from the original dataset for each subject and activity. Only the fields containing `mean` or `std` in the name were retained. The column names correspond to the name of the original measurement feature, simplified by converting to lower case, removing dashes and brackets and changing the prefixes `t` and `f` to `time` and `frequency` respectively. The values for each subject and activity are the means of those measurements as named in the header of that column.  The original dataset and its description are found at:[ UCI HAR Dataset ](http://archive.ics.uci.edu/ml/datasets/Smartphone-Based+Recognition+of+Human+Activities+and+Postural+Transitions " UCI HAR Dataset ")

* timebodyaccmeanx
* timebodyaccmeany
* timebodyaccmeanz
* timebodyaccstdx
* timebodyaccstdy
* timebodyaccstdz
* timegravityaccmeanx
* timegravityaccmeany
* timegravityaccmeanz
* timegravityaccstdx
* timegravityaccstdy
* timegravityaccstdz
* timebodyaccjerkmeanx
* timebodyaccjerkmeany
* timebodyaccjerkmeanz
* timebodyaccjerkstdx
* timebodyaccjerkstdy
* timebodyaccjerkstdz
* timebodygyromeanx
* timebodygyromeany
* timebodygyromeanz
* timebodygyrostdx
* timebodygyrostdy
* timebodygyrostdz
* timebodygyrojerkmeanx
* timebodygyrojerkmeany
* timebodygyrojerkmeanz
* timebodygyrojerkstdx
* timebodygyrojerkstdy
* timebodygyrojerkstdz
* timebodyaccmagmean
* timebodyaccmagstd
* timegravityaccmagmean
* timegravityaccmagstd
* timebodyaccjerkmagmean
* timebodyaccjerkmagstd
* timebodygyromagmean
* timebodygyromagstd
* timebodygyrojerkmagmean
* timebodygyrojerkmagstd
* freqbodyaccmeanx
* freqbodyaccmeany
* freqbodyaccmeanz
* freqbodyaccstdx
* freqbodyaccstdy
* freqbodyaccstdz
* freqbodyaccmeanfreqx
* freqbodyaccmeanfreqy
* freqbodyaccmeanfreqz
* freqbodyaccjerkmeanx
* freqbodyaccjerkmeany
* freqbodyaccjerkmeanz
* freqbodyaccjerkstdx
* freqbodyaccjerkstdy
* freqbodyaccjerkstdz
* freqbodyaccjerkmeanfreqx
* freqbodyaccjerkmeanfreqy
* freqbodyaccjerkmeanfreqz
* freqbodygyromeanx
* freqbodygyromeany
* freqbodygyromeanz
* freqbodygyrostdx
* freqbodygyrostdy
* freqbodygyrostdz
* freqbodygyromeanfreqx
* freqbodygyromeanfreqy
* freqbodygyromeanfreqz
* freqbodyaccmagmean
* freqbodyaccmagstd
* freqbodyaccmagmeanfreq
* freqbodybodyaccjerkmagmean
* freqbodybodyaccjerkmagstd
* freqbodybodyaccjerkmagmeanfreq
* freqbodybodygyromagmean
* freqbodybodygyromagstd
* freqbodybodygyromagmeanfreq
* freqbodybodygyrojerkmagmean
* freqbodybodygyrojerkmagstd
* freqbodybodygyrojerkmagmeanfreq