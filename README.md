**Crime Rate Prediction using Facebook Prophet
Project Overview**
This project aims to analyze and forecast crime trends in Chicago from the years 2005 to 2017. Using the Facebook Prophet library, this repository addresses the challenges of time series forecasting in the context of urban crime rates, providing insights that could help in planning and policy-making.

**Installation**
Before running the project, ensure that you have the following packages installed:

bash
Copy code
pip install pandas matplotlib seaborn cmdstanpy fbprophet
Note: Due to dependency conflicts with cmdstanpy, please ensure you are using the compatible versions as specified in the requirements.txt.

**Datasets**
The crime data used in this project spans from 2005 to 2017 and is segmented into three files:

**Chicago_Crimes_2005_to_2007.csv
Chicago_Crimes_2008_to_2011.csv
Chicago_Crimes_2012_to_2017.csv**
These files contain various attributes related to crime incidents, such as the type of crime, location, date, and time.

**Usage
To run the forecasting model:**

Ensure all datasets are placed in the /content/drive/MyDrive/Crime Datasets/ directory.
Execute the Jupyter notebook Crime_Rate_Prediction_using_Facebook_Prophet.ipynb to see the analysis and forecasting steps.
**Features**
**Data Cleaning:** 
Scripts for preprocessing the raw crime data.
**Visualization:** 
Use of matplotlib and seaborn for graphical representation of crime trends.
**Forecasting:** 
Application of the Prophet library to predict future crime rates based on historical data.
**Contributing**
Contributions to this project are welcome. Please fork the repository and submit a pull request with your suggested changes.
