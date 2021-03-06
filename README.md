# Song Popularity Prediction
A machine learning model which aims at predicting the commercial success of a song based on it's acoustic features and meta data. The dataset used is the [Million Song Dataset](http://millionsongdataset.com/) which is an open source dataset. A cleaned and compressed version of the dataset is available in the Datasets directory.

![alt text](https://wallpaperaccess.com/full/1432689.jpg)

## Project Flow - 
1. Scrapping the data from Billboard Archive. The data was scrapped using BeautifulSoup library. (Billboard100Scrapping.py)
2. Data Cleaning was done on the columns to fill missing values,drop redundant columns and a few transformations.(Data_cleaning.py)
3. Among the 55 features, the top 20 features were selected using recursive feature selection algorithm and were used for training.
4. The final model is an ensemble model which select the results from 5 algorithms as mentioned in the model.py file.

## Project Requirements - 
1. Python 3.x
2. Jupyter Notebook
3. Million Song Dataset (Subset)
