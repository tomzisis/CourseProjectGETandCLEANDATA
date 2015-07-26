                                                                            ###CODEBOOK
                                                                           



##COL   ##NAME                                 ##EXPLANATION

**1** **volunteer**           :   Identifier of each participant  (i.e: 1 -> 1st volunteer , 2 -> 2nd volunteer,..., 30 -> 30th volunteer)

**2** **activity**            :   Name of the activity (walking,walking upstairs,walking downstairs,sitting,standing,laying)


Columns 3-68 have the name structure (Feature)(Measure)(Direction) or (Feature)(Measure), that is :

**3** **tBodyAccmeanX**       
**4** **tBodyAccmeanY**
**5** **tBodyAccmeanZ**
**6** **tBodyAccstdX**
**7** **tBodyAccstdY**
**8** **tBodyAccstdZ**
**9** **tGravityAccmeanX**
**10** **tGravityAccmeanY**
**11** **tGravityAccmeanZ**
**12** **tGravityAccstdX**
**13** **tGravityAccstdY**
**14** **tGravityAccstdZ**
**15** **tBodyAccJerkmeanX**
**16** **tBodyAccJerkmeanY**
**17** **tBodyAccJerkmeanZ**
**18** **tBodyAccJerkstdX**
**19** **tBodyAccJerkstdY**
**20** **tBodyAccJerkstdZ**
**21** **tBodyGyromeanX**
**22** **tBodyGyromeanY**
**23** **tBodyGyromeanZ**
**24** **tBodyGyrostdX**
**25** **tBodyGyrostdY**
**26** **tBodyGyrostdZ**
**27** **tBodyGyroJerkmeanX**
**28** **tBodyGyroJerkmeanY**
**29** **tBodyGyroJerkmeanZ**
**30** **tBodyGyroJerkstdX**
**31** **tBodyGyroJerkstdY**
**32** **tBodyGyroJerkstdZ**
**33** **tBodyAccMagmean**
**34** **tBodyAccMagstd**
**35** **tGravityAccMagmean**
**36** **tGravityAccMagstd**
**37** **tBodyAccJerkMagmean**
**38** **tBodyAccJerkMagstd**
**39** **tBodyGyroMagmean**
**40** **tBodyGyroMagstd**
**41** **tBodyGyroJerkMagmean**
**42** **tBodyGyroJerkMagstd**
**43** **fBodyAccmeanX**
**44** **fBodyAccmeanY**
**45** **fBodyAccmeanZ**
**46** **fBodyAccstdX**
**47** **fBodyAccstdY**
**48** **fBodyAccstdZ**
**49** **fBodyAccJerkmeanX**
**50** **fBodyAccJerkmeanY**
**51** **fBodyAccJerkmeanZ**
**52** **fBodyAccJerkstdX**
**53** **fBodyAccJerkstdY**
**54** **fBodyAccJerkstdZ**
**55** **fBodyGyromeanX**
**56** **fBodyGyromeanY**
**57** **fBodyGyromeanZ**
**58** **fBodyGyrostdX**
**59** **fBodyGyrostdY**
**60** **fBodyGyrostdZ**
**61** **fBodyAccMagmean**
**62** **fBodyAccMagstd**
**63** **fBodyAccJerkMagmean**
**64** **fBodyAccJerkMagstd**
**65** **fBodyGyroMagmean**
**66** **fBodyGyroMagstd**
**67** **fBodyGyroJerkMagmean**
**68** **fBodyGyroJerkMagstd**

 where ,


(Feature) 


tBodyAcc                  : Body Acceleration time signal

tGravityAcc               : Gravity Acceleration time signal

tBodyAccJerk              : Body Acceleration time Jerk signal

tBodyGyro                 : Body angular velocity time signal

tBodyGyroJerk             : Body angular velocity time Jerk signal

tBodyAccMag               : Body Acceleration time signal Magnitude

tGravityAccMag            : Gravity Acceleration time signal Magnitude

tBodyAccJerkMag           : Body Acceleration time Jerk signal Magnitude 

tBodyGyroMag              : Body angular velocity time signal Magnitude

tBodyGyroJerkMag          : Body angular velocity time Jerk signal Magnitude

fBodyAcc                  : Body Acceleration frequency signal

fBodyAccJerk              : Body Acceleration frequency Jerk signal

fBodyGyro                 : Body angular velocity frequency signal

fBodyAccMag               : Body Acceleration frequency signal Magnitude

fBodyAccJerkMag           : Body Acceleration frequency Jerk signal Magnitude

fBodyGyroMag              : Body angular velocity frequency signal Magnitude

fBodyGyroJerkMag          : Body angular velocity frequency Jerk signal Magnitude



(Measure)   :   mean (mean value) or std (standard deviation) 


(Direction) :   X (X-axis) or Y (Y-axis) or Z (Z-axis)



* All features are normalized and bounded within [-1,1] *


##ADDITIONAL INFORMATIONS

The experiments have been carried out with a group of 30 volunteers within an age bracket of 19-48 years. 

Each person performed six activities (WALKING, WALKING_UPSTAIRS, WALKING_DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone (Samsung Galaxy S II) on the waist.  

The obtained dataset has been randomly partitioned into two sets, where 70% of the volunteers was selected for generating the training data and 30% the test data. 

The features selected for this database come from the accelerometer and gyroscope 3-axial raw signals tAcc-XYZ and tGyro-XYZ. These time domain signals (prefix 't' to denote time) 

were captured at a constant rate of 50 Hz. Then they were filtered using a median filter and a 3rd order low pass Butterworth filter with a corner frequency of 20 Hz to remove noise. 

Similarly, the acceleration signal was then separated into body and gravity acceleration signals (tBodyAcc-XYZ and tGravityAcc-XYZ) using another low pass Butterworth filter with a corner frequency of 0.3 Hz. 

Subsequently, the body linear acceleration and angular velocity were derived in time to obtain Jerk signals (tBodyAccJerk-XYZ and tBodyGyroJerk-XYZ). 

Also the magnitude of these three-dimensional signals were calculated using the Euclidean norm (tBodyAccMag, tGravityAccMag, tBodyAccJerkMag, tBodyGyroMag, tBodyGyroJerkMag). 

Finally a Fast Fourier Transform (FFT) was applied to some of these signals producing fBodyAcc-XYZ, fBodyAccJerk-XYZ, fBodyGyro-XYZ, fBodyAccJerkMag, fBodyGyroMag, fBodyGyroJerkMag. 

(Note the 'f' to indicate frequency domain signals). 

