                                      #CODEBOOK
                                                                                                        

**Col1** **volunteer**           :   Identifier of each participant  (i.e: 1 -> 1st volunteer , 2 -> 2nd volunteer,..., 30 -> 30th volunteer)

**Col2** **activity**            :   Name of the activity (walking,walking upstairs,walking downstairs,sitting,standing,laying)


Columns 3-68 have the name structure **(Feature)(Measure)(Direction)*8 or **(Feature)(Measure)**, that is :

**Col3** **tBodyAccmeanX**       

**Col4** **tBodyAccmeanY**  

**Col5** **tBodyAccmeanZ**  

**Col6** **tBodyAccstdX** 

**Col7** **tBodyAccstdY** 


**Col8** **tBodyAccstdZ**

**Col9** **tGravityAccmeanX**

**Col10** **tGravityAccmeanY**

**Col11** **tGravityAccmeanZ**

**Col12** **tGravityAccstdX**

**Col13** **tGravityAccstdY**

**Col14** **tGravityAccstdZ**

**Col15** **tBodyAccJerkmeanX**

**Col16** **tBodyAccJerkmeanY**

**Col17** **tBodyAccJerkmeanZ**

**Col18** **tBodyAccJerkstdX**

**Col19** **tBodyAccJerkstdY**

**Col20** **tBodyAccJerkstdZ**

**Col21** **tBodyGyromeanX**

**Col22** **tBodyGyromeanY**

**Col23** **tBodyGyromeanZ**

**Col24** **tBodyGyrostdX**

**Col25** **tBodyGyrostdY**

**Col26** **tBodyGyrostdZ**

**Col27** **tBodyGyroJerkmeanX**

**Col28** **tBodyGyroJerkmeanY**

**Col29** **tBodyGyroJerkmeanZ**

**Col30** **tBodyGyroJerkstdX**

**Col31** **tBodyGyroJerkstdY**

**Col32** **tBodyGyroJerkstdZ**

**Col33** **tBodyAccMagmean**

**Col34** **tBodyAccMagstd**

**Col35** **tGravityAccMagmean**

**Col36** **tGravityAccMagstd**

**Col37** **tBodyAccJerkMagmean**

**Col38** **tBodyAccJerkMagstd**

**Col39** **tBodyGyroMagmean**

**Col40** **tBodyGyroMagstd**

**Col41** **tBodyGyroJerkMagmean**

**Col42** **tBodyGyroJerkMagstd**

**Col43** **fBodyAccmeanX**

**Col44** **fBodyAccmeanY**

**Col45** **fBodyAccmeanZ**

**Col46** **fBodyAccstdX**

**Col47** **fBodyAccstdY**

**Col48** **fBodyAccstdZ**

**Col49** **fBodyAccJerkmeanX**

**Col50** **fBodyAccJerkmeanY**

**Col51** **fBodyAccJerkmeanZ**

**Col52** **fBodyAccJerkstdX**

**Col53** **fBodyAccJerkstdY**

**Col54** **fBodyAccJerkstdZ**

**Col55** **fBodyGyromeanX**

**Col56** **fBodyGyromeanY**

**Col57** **fBodyGyromeanZ**

**Col58** **fBodyGyrostdX**

**Col59** **fBodyGyrostdY**

**Col60** **fBodyGyrostdZ**

**Col61** **fBodyAccMagmean**

**Col62** **fBodyAccMagstd**

**Col63** **fBodyAccJerkMagmean**

**Col64** **fBodyAccJerkMagstd**

**Col65** **fBodyGyroMagmean**

**Col66** **fBodyGyroMagstd**

**Col67** **fBodyGyroJerkMagmean**

**Col68** **fBodyGyroJerkMagstd**

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



*All features are normalized and bounded within [-1,1]*


###ADDITIONAL INFORMATIONS

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

