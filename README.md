# House Price Prediction with Regression Techniques

Welcome to the House Price Prediction project! 🏡💰 In this comprehensive end-to-end guide, we will walk through every step — from downloading the dataset to hosting a predictive web application on AWS EC2 using Flask and Nginx.

## Table of Contents
1. [Introduction](#introduction)
2. [Steps](#steps)
    1. [Downloading Dataset from Kaggle](#downloading-dataset-from-kaggle)
    2. [Cleaning the Dataset in Jupyter Notebook](#cleaning-the-dataset-in-jupyter-notebook)
    3. [Building Various Models](#building-various-models)
    4. [Building Flask Server](#building-flask-server)
    5. [Creating Simple Web UI](#creating-simple-web-ui)
    6. [Hosting on AWS EC2 Instance](#hosting-on-aws-ec2-instance)
3. [Requirements](#requirements)
4. [Source Code](#source-code)

## Introduction <a name="introduction"></a>

This project aims to predict house prices using regression techniques. The process involves downloading the dataset from Kaggle, cleaning it, building various regression models, creating a Flask server, designing a simple web UI, and finally hosting the entire application on an AWS EC2 instance.

## Steps<a name="steps"></a>

### Downloading Dataset from Kaggle <a name="downloading-dataset-from-kaggle"></a>

To get started, head over to Kaggle and download the dataset. Make sure you have a Kaggle account, and follow the instructions to download the dataset relevant to house prices.

### Cleaning the Dataset in Jupyter Notebook <a name="cleaning-the-dataset-in-jupyter-notebook"></a>

Open the Jupyter Notebook provided in the source code. This step involves exploring the dataset, handling missing values, and performing any necessary preprocessing to ensure the data is ready for modeling.

### Building Various Models <a name="building-various-models"></a>

Explore different regression techniques such as linear models, Lasso, SVM, Random Forest, and Keras Regression. The source code includes implementations for each model, allowing you to compare their performance.

### Building Flask Server<a name="building-flask-server"></a>

Once you have chosen the best model, build a Flask server to deploy the model as an API. This step involves creating endpoints to receive input data for predictions.

### Creating Simple Web UI <a name="creating-simple-web-ui"></a>

Design a simple web UI to interact with the Flask server. Users can input relevant details, and the server will respond with the predicted house price.

<img align="center" src="Price Prediction example on hosted site.webp" alt="Web UI" />

### Hosting on AWS EC2 Instance <a name="hosting-on-aws-ec2-instance"></a>

Utilize the AWS EC2 instance for hosting your Flask application. This section provides step-by-step guidance on deploying your application on the cloud.

## Requirements <a name="requirements"></a>

Make sure you have the following libraries installed:

- pandas
- numpy
- matplotlib
- machine learning library (specific to your chosen model)
- Flask (developed in PyCharm)
- Nginx server (download available [here](https://nginx.org/))

## Source Code<a name="source-code"></a>

The source code for each step is provided in the respective directories. Feel free to explore and modify the code to suit your specific requirements.

Now, let's embark on this exciting journey of predicting house prices with regression techniques and showcasing it through a user-friendly web interface! 🌐✨
