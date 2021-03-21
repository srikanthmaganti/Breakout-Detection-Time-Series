# Breakout-Detection-Time-Series

All the files will be in pdf and ipynb format

1.Removing the outliers and sensor values in initial stages

2.EDA file represents how data analysis is done for each of the sensor values and also comprehensively

3.Applying moving variance for the sensor values in a dataframe

4.Examining all the values with tukey hinge value which are greater than 0.75 quartile

5.Labeled Y_values according to the threshold(s(t)>threshold) and X values as (S(t-1),S(t-2),S(t-3).....)

6.Initially send these values into Recurrent Neural Networks(RNN,LSTM,GRU) for each sensor prediction

7.Comprehensive analysis of all sensors combined is done in comprehensive_analysis_breakout_detection by considering all the sensor values into consideration
 
8.Comprehensive analysis is done for the past 8 steps data and y label is assigned by root mean square of all sensors data.
