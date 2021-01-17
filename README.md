## MUGLA SITKI KOCMAN UNIVERSITY 
### COMPUTER ENGINEERING 
### DATA MINING (CENG 3521) FINAL PROJECT

# ONLINE SHOPPERS INTENTION 

![1](https://www.further.co.uk/wp-content/uploads/2019/04/onlineshoppers002.jpg)
##### Data Set Information:

The dataset consists of feature vectors belonging to 12,330 sessions.
The dataset was formed so that each session would belong to a different user in a 1-year period to avoidany tendency to a specific campaign, special day, user profile, or period.

##### Dataset Origin:

https://archive.ics.uci.edu/ml/datasets/Online+Shoppers+Purchasing+Intention+Dataset

##### Source:

C. Okan Sakar
Department of Computer Engineering, Faculty of
Engineering and Natural Sciences, Bahcesehir University,
34349 Besiktas, Istanbul, Turkey

Yomi Kastro
Inveon Information Technologies Consultancy and Trade,
34335 Istanbul, Turkey

##### Relevant Papers

* [Importing Data](#1)
* [First-Looking to Data and Analyzing](#2)
    * [First Looking to Df](#3)
    * [Information](#4)
    * [Information about Numerical Values](#5)
* [EDA and Pre-Processing](#6)
    * [Numerical to Categorical](#7)
    * [Distribution of Categorical Features with Histogram](#8)
    * [Month Setting](#9)
    * [Administrative Settings](#10)
    * [Dropping Some Columns](#11)
    * [Outliers and Removing Them](#12)
    * [Correlation on Categoricals](#13)
    * [Changing Type Of Some Columns to Prepare the Models](#13)
* [Classification](#14)
    * [SGDClassifier](#15)
        * [Creating Model](#21)
        * [Fitting](#22)
        * [Predicting](#23)
        * [Accuracy](#24)
        * [Cross Validation](#25)
    * [MLPClassifier](#16)
        * [Creating Model](#26)
        * [Fitting](#27)
        * [Predicting](#28)
        * [Accuracy](#29)
        * [Cross Validation](#30)
    * [MLPClassifier with Different Hidden Layer Sizes](#31)
* [Clustering](#17)
    * [PCA](#18)
        * [Creating Model](#32)
        * [Fitting](#33)
        * [Explained Variance Ratios](#34)
        * [Selecting Number of PC Components](#35)
        * [Getting X and Y For Each Components](#36)
        * [Plotting](#36)
    * [K-Means](#19)
        * [Optimum K](#38)
        * [Creating Model](#39)
        * [Fitting](#40)
        * [Plotting K-Means with Optimum K](#41)
        * [Plotting with Cluster Centers](#42)
        * [Plotting with Two Different K](#43)
* [Classification](#20)
    * [k-NN](#20)
        * [Finding Optimum K](#44)
        * [Creating Model with Optimum K](#45)
        * [Fitting](#46)
        * [Prediction](#47)
        * [Accuracy](#48)
        * [Confusion Matrix](#49)
