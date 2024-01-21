## As for rectified data:
- all the labelled datapoints (the first column starting from the 11th row in n_sensor_data.xlsx) in every sheets should be added with am unique offset
- the value of the offset is always in D13 entry in each sheet.
- the offset can be negative, after adding the negative offset, negative datapoints can be ignored 


data_preprocessing: Compile data from raw data files, relabel & detrend data\
feature_extraction: extract time and frequency domain features for proximity and IMU sensors; detect eating period with XGBoost classifier\
model_training: detect eating period with LSTM\
chewing_frequency: chewing count estimation with PSO\
Put original_data and labelled data folders under the same directory
