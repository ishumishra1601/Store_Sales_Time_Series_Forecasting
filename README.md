# Store_Sales_Time_Series_Forecasting
Store Sales Forecasting using Time-Series Analysis on Corporación Favorita Data


## Project Overview
This project aims to forecast store sales for a large Ecuadorian-based grocery retailer, Corporación Favorita, using time-series analysis. The project uses various datasets including Train, Test, Transactions, Holidays Events, Stores, and Sample Submissions to develop a forecasting model based on LSTM.

## Methodology
### Data Exploration and Cleaning
The first step in the project involved exploring and cleaning the data. This step involved creating a function to get the head, info, statistics, shape, columns, and null values of the data, and treating the null values. This step ensured that the data was clean and ready for analysis.

### Data Visualization
The second step involved creating plots and graphs to visualize the data of oil, stores, transactions, and holidays dataset. This step involved converting the date column to datetime, and visualizing the data to identify any trends and patterns in the data.

### Data Merging
The third step involved merging all the datasets into a single combined dataset. This step involved identifying common fields in the datasets and merging them appropriately to ensure a comprehensive dataset for analysis.

### Encoding Categorical Values
The fourth step involved encoding categorical values in the dataset into numerical values that could be used for analysis. This step involved using one-hot encoding for different categorical values and dropping unnecessary columns for prediction.

### Function to create dataframe with WINDOW = 1 and LAG = 1 for Time Series Analysis
The fifth step involved creating a function to create a dataframe with WINDOW = 1 and LAG = 1 for time-series analysis. This step involved splitting the data into training and testing datasets, and creating a time-series dataset with a window size of 1 and lag of 1.

### Modelling with LSTM
The final step involved building a time-series forecasting model using LSTM. This step involved training the model on the training dataset and testing the model on the testing dataset to evaluate its performance. The model achieved an accuracy of 93.9% on the testing dataset, indicating that it could accurately forecast store sales for the Ecuadorian-based grocery retailer, Corporación Favorita.

### Results
The project successfully demonstrated the use of time-series analysis and LSTM modelling to forecast store sales for a large grocery retailer. The project highlights the importance of data exploration and cleaning, data visualization, and encoding categorical values in preparing data for analysis. Additionally, the project provides insights into the techniques and methods used to develop a time-series forecasting model using LSTM.

### Conclusion
The project demonstrates the effectiveness of using time-series analysis and LSTM modelling to forecast store sales. The accuracy of 93.9% indicates that the model can accurately predict store sales for the Ecuadorian-based grocery retailer, Corporación Favorita. The project provides valuable insights into the techniques and methods used to develop a time-series forecasting model using LSTM.

### Future Work
The project could be extended in the future by exploring other time-series forecasting techniques and models such as ARIMA, Prophet, and XGBoost. Additionally, the project could be extended to include more features and datasets to improve the accuracy of the forecasting model. Finally, the project could be deployed as a web application to provide a user-friendly interface for users to forecast store sales.
