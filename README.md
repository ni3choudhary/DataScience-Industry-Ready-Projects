# Git and Github

## Task 2:

### Consider that your want to start an open-source project in your organization. Perform all the standard operation to create a repository with minimal permision for all the users. It should contain.

1. Proper open source structure
2. Proper Readme
3. Add 2 collaborator
4. Host GitHub Pages using settings (Designed to host your personal, organization, or project pages from a GitHub repository)


## Rainfall-Prediction-In-Australia-Deployment

[![Kaggle](https://img.shields.io/badge/Dataset-Kaggle-blue.svg)](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package) ![Python 3.6](https://img.shields.io/badge/Python-3.6-brightgreen.svg)

• This repository consists of files required for end to end implementation of Rain Prediction in Australia ___Machine Learning Web App___ created with ___Flask___ on ___Heroku___ platform.

### Problem statement:
A ML project with EDA and model that helps in predicting next-day rain by training classification models on the target variable RainTomorrow.

### Dataset
You can find the dataset [here.](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)

### Dependencies:
* Python 
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Scikit-Learn
* Catboost
* Tensorflow
* Flask 

## setup
To create a project from scratch use following steps - -

- Clone the repository : https://github.com/ni3choudhary/Rainfall-Prediction-In-Australia-Deployment.git
- Inside the project root directory, Create Python Virtual Environment using below command.
```console
$ python3 -m venv venv
``` 

Activate Virtual Environment
```console
$ .venv/bin/activate 
          OR
$ .\venv\Scripts\activate
```
Install Libraries using below command
```console
$ pip install -r requirements.txt
```
- Run jupyter notebook to get the pickle file inside **Model** directory.

- Copy that pickle file and create a folder **Model** inside **flask** directory and paste the pickle file.

- Inside the **flask** directory run **app.py** on terminal to start local server.
```console
$ python app.py
```

• If you want to view the deployed model, click on the following link: Deployed at: https://rainfall-prediction-australia.herokuapp.com/

• Please do ⭐ the repository, if it helped you in anyway.

