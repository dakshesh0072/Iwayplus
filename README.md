There is RSSI data from ground to third floor of the R&I Park.
Add the "Localization_project-main.zip" folder to the path and rename it accordingly to the unzip code.
There are four jupyter notebooks for each floor.
First run the unzip code, then the RSSI generation code and then the localization_2 code to get the MAE(Mean Absolute error) and MSE(Mean squared error).
For the prediction of coordinates of continuous path, you can add the .csv file of continuous data to the path, which is of the A block of the ground floor.
Then run the Localization_3 code which is in the .iypnb file of the ground floor only, that will give the set of x and y coordinates for that continuous RSSI data.
Then can run the plotting code to plot the predicted coordinates to get the path estimation.
LSTM model reqires distance datasets and input-output functions need to built according to that.
