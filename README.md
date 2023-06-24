# JBG050-group11
# Project Description
This project develops a predictive policing model to forecast residential burglary hotspots in Barnet, London, using data analysis of various datasets like historical crime data, demographic information, and police workforce data. However, the project extends beyond just predictive analysis and carefully considers ethical implications, particularly using sensitive personal data. While aiming for accurate predictions, the project also sets a standard for ethical data handling and fairness in predictive policing. Facebook Prophet was the model used for these predictions since it appeared to be the most accurate.

# File & Folder Summary
Folders:
1. Datasets:
   includes all the datasets used (initial historical crime data, police workforce, population)

Files:
1. requirements.txt: file including all the libraries used for this project
2. data_exploration_arima.ipynb: data cleaning, EDA, predictions for Barnet burglary rates using ARIMA and SARIMA models
3. forecast_prophet.ipynb: predictions for Barnet burglary rates using Facebook Prophet model (final model)
4. DashboardCodeFinal.ipynb: most important and insightful plots, alongside with an interactive visualization where the user can choose month, year, and ward of Barnet to get the number of hours needed according to our predictions using Prophet
5. LSTM.ipynb: predictions for Barnet burglary rates using LSTM model
6. forecast_holt_winters.ipynb: predictions for Barnet burglary rates using Holt-Winters model


# How to run the code
1. run the requirements.txt file in order to get all the necessary libraries
2. download the files and folders from the folder Dataset, and change the directory in the ipynb files with the one at yours
3. run the data_exploration_arima.ipynb in order to get the data cleaning, eda and arima predictive model, which was one of the models we tried
4. run the forecast_prophet model.ipynb to get the predictions by using the final model-Facebook Prophet, since it performed the best, with higher accuracy and lower MAE
5. run the DashboarCodeFinal.ipynb in order to get the code used for the dashboard, and actually be able to explore the group's dashboard to get some useful insights
6. optional (since were not used in the end):
   run the forecast_holt_winters and/or LSTM if you want to check other two models we tried implementing for predicting burglary rates in Barnet


