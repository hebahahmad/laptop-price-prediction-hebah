Laptop Price Predictor


There are many laptop manufacturers who are unwilling to share information about their products, so consumers are often unable to make accurate comparisons of prices. In this project, we propose to develop a machine learning-based laptop price predictor that can estimate the price of a laptop based on its specifications using machine learning techniques. Our approach is essentially the collection of data pertaining to laptop specifications and prices, followed by training a machine learning model to predict laptop prices based on these specifications. The following sections will explore machine learning algorithms, including linear regression, decision trees, and K neural networks. This is so we can determine which is the most accurate at predicting the future.
We will evaluate our model's performance on a separate laptop specifications and prices dataset. We will compare the predicted prices with the actual prices to measure our predictions' accuracy. Finally, we will develop a web application that allows users to input laptop specifications and receive an estimated price based on our model.
The significance of our project lies in the fact that it solves a common problem faced by consumers when shopping for laptops - the lack of transparency in pricing when comparing laptops and their options. As a result of developing a machine learning-based laptop price predictor, we empower consumers to make informed purchase decisions without relying solely on manufacturers' information.

This is a machine learning project that predicts the price of a laptop based on its features. It uses a dataset of laptops from various brands and with various specifications to train a regression model that can predict the price of a laptop given its features.

Installation
To run this project, you will need to install Python and the following libraries:

pandas
numpy
scikit-learn
matplotlib
You can install these libraries using pip:


pip install pandas numpy scikit-learn matplotlib


Once you have installed the libraries, you can run the project by executing the app.py script.

Usage
To use the laptop price predictor, simply input the features of the laptop you want to predict the price of into the predict_price function in the app.py file.
The features should be in the form of a pandas DataFrame with the following columns:
Laptop company,
type of laptop,
Ram size,
operating system, 
weight, 
touchscreen, 
IPS, 
PPI, 
CPU Name,
HDD, 
SSD,
GPU brand.
![image](https://user-images.githubusercontent.com/125111330/236100300-e9e4527f-0acc-4bd1-bced-c4fa3a41bfbd.png)



this is the link https://laptop-price-prediction-hebah.herokuapp.com/
