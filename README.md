# Netflix-Stockprice-Prediction
In this project, I am predicting the stock price of Netflix using the LSTM(Long Short Term Memory) model.

**Description of Data:** 1. I have considered a dataset of Netflix Stock Prices.
                        2. This dataset contains data for 5 years i.e. from 5th Feb 2018 to 5th Feb 2022.
                        3. This dataset contains 1009 records having 7 features i.e. Date, Open, High, Low, Close, Adj Close, and Volume.

**Data Exploration:** In this, I am exploring the Netflix Stock Price dataset about the shape of the dataset, their datatypes, and statistical measures like mean, 
                     median, mode, etc.
                   data.info() gives information about the dataset i.e. number of columns, count of each column, and datatype of each column.
                   data.shape gives the shape of the dataset i.e. the number of rows and columns present in the dataset.
                   data.describe() gives statistical measures
                   data.corr() gives a correlation matrix.


**Data Cleaning:** In this I am going to check whether there are any wrong values or null values present that will be cleaned in data cleaning.
                    Outliers are also replaced with the Q3(75%) in Data Cleaning only. After doing the Data Cleaning raw data is converted into well structured 
                    data.

**Data Visualization:** In Data Visualization we see a distribution of each column with the help of various plots. In this project, I have used Box plot to identify 
                         whether there is an outlier present or not, the heatmap is used to display data values in a two-dimensional matrix format, where each value 
                         is represented by a color  and a Pairplot is used to find the relationship between each column.


**Data Preprocessing:** Data preprocessing is a crucial step in the data analysis and machine learning pipeline. It involves cleaning, organizing, and 
                        transforming  raw data into a format that is suitable for analysis or model training. Using MinMaxScaler for  scaling each feature in a 
                        specific region that is generally between 0 and 1.

Splitting the data into training data and testing data.

 **Model Development:**
Building the prediction model was the heart of the project. Armed with Python and powerful libraries like Pandas, Scikit-Learn, and TensorFlow, I engineered features, fine-tuned parameters, and experimented with various machine learning algorithms. The goal was to create a model that could generalize well to unseen data, making accurate predictions.
