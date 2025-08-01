# Air Quality Forecasting
FB Prophet, or simply Prophet, is an open-source time series forecasting procedure developed by Facebook's Core Data Science team. It's designed to be user-friendly, particularly for data with strong seasonality and trend changes, and is available in both Python and R.

#### Importing important python libraries
* Importing necessary Python Library
* Using the *Pandas* for reading `csv files`
  
#### Data Preprocessing & Cleaning
* After Reading the file, cleaning and handling the missing values and other column issues.
* Missing values are present but they are changed into -200
* Decimal Points are present in the form of comma.
* Removing the null rows and columns
* After identifying -200 they are converted into the mean of that particular column

#### FB Prophet Model Prerequistes & Training
* FB Prophet only takes two column - *ds (YYYY/MM/DD HH:MM:SS)* and *y (RH)*.
* To meet this criteria, we have to convert the date format and combine date and time column as *ds*.
* ds column needs to be in **"date/time format"**
* Two task can be performed from this dataset:
  1. Forecasting
  2. Regression
* Installing the FB Prophet and using it for forecasting.
* Training it on **data** dataframe made consisting only *ds* and *y* columns.
* And then prediction is done.
  
#### Attribute Change
* Same process is done using another attribute *y* - **CO(GT)**
* Another prediction model for it.
  
#### Visualizations
* Visualization done by plot method present in Prophet model/class
* Scatter plot and line graph can be seen of the predicted values.
* Attribute of the **RH** and **CO(GT)** are shown in graphs.
* **Plotly graph visualization** is also used - It is the interactive graph visualization.
