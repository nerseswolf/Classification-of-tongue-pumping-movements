# Machine Learning
## The aim of the project is to classify tongue pumping movements.

The data are available in the file pumpFeatures.xlsx.

### Features:

| Feature name | Description  |
| ------------- | ------------- |              
| 'Subject' | Index of test person |  
| 'StartTime', 'StopTime' | Start and end times of hill | 
| 'Length' | Length of hill | 
| 'MinMaxDif' | Difference between highest and lowest value of hill | 
| 'Steepness' | Steepness of hill | 
| 'SquaredSum' | Area under hill | 
| 'EMG' | Average of EMG onset detection | 
| 'EMGPower' | Power of EMG signal in hill window | 
| 'EMGSlope' | Rise of EMG signal in hill window | 
| 'NumOfLines' | Number of lines in a hill | 
| 'Hight' | Largest value of hill | 
| 'SqSumUp' | Area under rising flank of a hill | 
| 'SqSumDown' | Area under falling flank of a hill | 
| 'BIMassCenter' | Centre of gravity of hill on x-axis | 
| 'Sax1', - 'Sax8' | Symbols of bioimpedance signal | 
| 'Sax1Emg' - 'Sax8Emg' | Sax symbols of EMG signal | 

  

  



1. Feature calculation from the given data set (for example: PCA - Principal Component Analysis, Feature importances with forests of trees etc. )

2. Model selection (Decision Tree Classifier, Random Forest Classifier, K-Nearest Neighbors Classifier, SVC - Support Vector Classification, Linear SVC etc. )

3. Training of the classifier (Scaling of data, Split data set into training and test data, Optimization of the cost function, Determination of the free parameters of the model)

5. Evaluation of the classifier (sensitivity, specificity, pressure, F-score, accuracy etc. )
