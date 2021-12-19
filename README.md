# Heart Attack Risk predictor
Main Aim of this project is to predict whether a person is having a risk of heart attack or not, using Automated Machine Learning Techniques. 

## Table of Content
  * [Demo](#demo)
  * [Problem Statement](#problem-statement)
  * [Approach](#approach)
  * [Technologies Used](#technologies-used)
  * [Installation](#installation)
  * [Bugs & Logs](#bugs--logs)
  * [Contributors](#contributors)

## Demo
Link: [https://pimaindiansdiabetes.herokuapp.com/](https://pimaindiansdiabetes.herokuapp.com/)

![Screenshot](Capture.PNG)
![Screenshot](Capture2.PNG)


## Problem Statement
A heart attack occurs when one or more of your coronary arteries becomes blocked. Over time, a buildup of fatty deposits, including cholesterol. form substances called plaques, which can narrow the arteries (atherosclerosis). This condition, called coronary artery disease, causes most heart attacks. 

![Screenshot](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.kaggle.com%2Fsaurabhshahane%2Feval-ml-automl&psig=AOvVaw2IKhg4q2ThjQHr2Kn4C0lZ&ust=1639987000263000&source=images&cd=vfe&ved=0CAsQjRxqFwoTCPi8qOmx7_QCFQAAAAAdAAAAABAD)
EvaIML an open-source AutoML library written in python that automates a large part of the machine learning process and we can easily evaluate which machine learning pipeline works better for the given set of data. 

## Approach
Data Exploration : I started exploring dataset using pandas,numpy,matplotlib and seaborn.

Data visualization : Ploted graphs to get insights about dependend and independed variables.

Feature Engineering : Removed missing values and created new features as per insights.

Model Building & Testing : Tried many machine learning algorithms and checked the base accuracy to find the best fit.

Pickle File : Selected model as per best accuracy and created pickle file.

User Interface & deployment :  Created an UI with a form that takes all the necessary inputs from user and shows the output.
                          After that I have deployed project on heroku.
## Technologies Used
 
   1. Python 
   2. Sklearn
   3. Evalml
   4. SVM
   5. GridSearchCV
   6. Pandas, Numpy 

## Dataset
[Download here](https://www.kaggle.com/uciml/pima-indians-diabetes-database/download)

## Installation
Click here to install [python](https://www.python.org/downloads/). To install the required packages and libraries, run this pip command in the project directory after cloning the repository:
```bash
git clone https://github.com/hrishikeshkini/pima-indians-diabetes.git
pip install -r requirements.txt
```
If pip is not already installed, Follow this [link](https://pip.pypa.io/en/stable/installation/)

## Bugs & Logs

1. If you find a bug, kindly open an issue and it will be addressed as early as possible. [Open](https://github.com/hrishikeshkini/pima-indians-diabetes/issues)
2. Under localhost, logging is performed for all the actions and its stored onto logs.txt file
3. When the app is deployed on heroku, logs can be viewed on  heroku dashboard or CLI.

## Contributors
  [Hrishikesh Kini](https://github.com/hrishikeshkini)
