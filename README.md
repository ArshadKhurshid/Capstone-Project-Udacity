
# Machine Learning Engineer Nanodegree

## Supervised Learning

### Project: Capstone Project

####  Install

This project requires Python 3.6 and the following Python libraries installed:

    NumPy
    Pandas
    matplotlib
    scikit-learn

You will also need to have software installed to run and execute an iPython Notebook

We recommend to install Anaconda, a pre-packaged Python distribution that contains all of the necessary libraries and software for this project.

#### Code

Code is provided in the CapstoneProject.ipynb notebook file. It uses the HR_comma_sep.csv dataset file. Code uses numpy, python, matplotlib and scikit learn libraries. Code uses classification technique of Supervised Learning to train the model. Code has implemented ADABoost Classifier, Gradient Descent Classifier, SVM and Stochastic gradient Descent to calculate performance based on the different methods of training using different techniques.

#### Run

In a terminal or command window, navigate to the top-level project directory capstone_project/ (that contains this README) and run one of the following commands:


```python
ipython notebook CapstoneProject.ipynb
```

or


```python
jupyter notebook CapstoneProject.ipynb
```

This will open the iPython Notebook software and project file in your browser.

#### Data

This data set contains total of 14999 rows and 10 columns. Target variable (left) is imbalance dataset. It contains 3751 records of employee who have left the company. 11428 records of employee who stayed in the company. Here we are trying to predict employee who can quit. Dataset has been extracted from Kaggle.

Dataset Link: https://www.kaggle.com/ludobenistant/hr-analytics

##### Features

* satisfaction_level : Level of Satisfaction
* last_evaluation :Time since Last performance Evaluation
* number_project :Number of Project completed while at work
* average_montly_hours : Average monthly hours at workplace
* time_spend_company : Number of years spent in the company
* Work_accident : Whether the employee had a workplace accident
* promotion_last_5years: Wehter employee was promoted in last 5 years
* sales : Department they work for
* Salary : Relative level of Salary(high)

##### Target Variable

* left : Whether employee left the workplace or not (0 - stayed and 1 - Left)
