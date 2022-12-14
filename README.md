# Telecom Churn Case Study

> To build a model to predict churning customers for a Telecom company based on temporal behaviour

## Table of Contents

- [Overview Business Understanding](#overview-business-understanding)
- [Problem Statement Business Objectives](#problem-statement-business-objectives)
- [Data in depth](#data-in-depth)
- [Approach](#approach)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## Overview Business Understanding

In the telecom industry, customers are able to choose from multiple service providers and actively switch from one operator to another. In this highly competitive market, the telecommunications industry experiences an average of 15-25% annual churn rate. Given the fact that it costs 5-10 times more to acquire a new customer than to retain an existing one, customer retention has now become even more important than customer acquisition.

## Problem Statement Business Objectives

For many incumbent operators, retaining high profitable customers is the number one business goal. To reduce customer churn, telecom companies need to predict which customers are at high risk of churn. In this project, you will analyze customer-level data of a leading telecom firm, build predictive models to identify customers at high risk of churn.

The company wants to know:

- Main goal is to build a machine learning model that is able to predict churning customers based on the features provided for their usage, and
- Identify important variables that are strong predictors of churn.
- Also, identify high value cutomer to recommend strategies to manage customer churn based on their usage.

### Want to

- Understand the driving factors (or driver variables) to predict churning customers based on the features provided for their usage, i.e. the variables which are strong indicators.
- To build a model to predict churning customers for a Telecom company based on temporal behaviour

## Data in depth

- We are going to analyze datasets,
- The datasets contains details information related of the Telecom Churn.
- The dataset comprises of 69999 observations of 172 columns.

## Approach

#### Understanding the Dataset

- To gain insights from data we must look into each aspect of it very carefully. We will start with observing few rows and columns of data both from the starting and from the end.

#### Preprocessing

- We will deal with erroneous, missing and outliers values of columns.
- Correlation between different columns
- See how preprocessing have transformed our dataset.
- Derive new data from existing data to get more insite

#### Exploratory Data Analysis on Loan Dataset

- Try to find out answers of some set of questions

#### Build Model after Dataset split

- Build model & validate results after split dataset in train & test repsectiviey using multiple linear regression, Tree and Random Forest model using with and without PCA.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions

Based on our analysis and as per our final Model and with the references in changes in the coefficients after regularization, the best model to predict the churn is observed to be **Random Forest** based on the accuracy as performance measure.

- The incoming calls (with local same operator mobile/other operator mobile/fixed lines, STD or Special) plays a vital role in understanding the possibility of churn. Hence, the operator should focus on incoming calls data and has to provide some kind of special offers to the customers whose incoming calls turning lower.

After cleaning the data, we broadly employed three models as mentioned below including some variations within these models in order to arrive at the best model in each of the cases.

**Logistic Regression :**

- Logistic Regression with RFE Logistic regression with PCA Random Forest For each of these models, the summary of performance measures are as follows:

**Logistic Regression**

- Train Accuracy : ~80% . Test Accuracy : ~85%

**Logistic regression with PCA**

- Train Accuracy : ~91% . Test Accuracy : ~90%

**Decision Tree with PCA:**

- Train Accuracy : ~92% . Test Accuracy : ~90%

**Random Forest with PCA:**

- Train Accuracy :~ 92% . Test Accuracy :~ 91%

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Technologies Used

- Python
- Numpy
- Panda
- Matplotlib
- Seaborn
- SMOTE
- Jupyter Notebook

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Contact

Created by [@pravin691983] - feel free to contact me!

<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
