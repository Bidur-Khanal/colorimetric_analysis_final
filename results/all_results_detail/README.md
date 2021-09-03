All the values we used in table are obtained from these two sub-folders. 
* "food color" contains experiment results for food dye.
* "pesticide" contains experiment results for pesticide.

***
Inside Each sub-folders, you will find 4 or 2 csv files.
* cross_validation_downsampled_image.csv: contains all crossvalidation split results when all downsampled pixels are used as features.
* cross_validation_mean_value.csv: contains all crossvalidation split results when mean values are used as features.
* test_downsampled_image.csv: contains all test results when all downsampled pixels are used as features.
* test_mean_value.csv: contains all test results when mean values are used as features.

***
Inside folders containing ANN
* cross_validation_mean_value.csv:         Cross-validation Results for Mean color as features
* test_mean_value.csv:                     Test Results for Mean color as features

***
Inside folders containing CNN
* cross_validation_CNN.csv:         Cross-validation Results for downsampled image as features
* test_CNN.csv:                     Test Results for downsampled image as features

*Please Refer to Column Titled "remarks", it describes the rows in all the tables

