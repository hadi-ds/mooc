#Empower edX

This repository contains details of data project I did during my fellowship at Insight Data Science. The goal is to study ways of increasing student engagement in **_massive open online courses_** (mooc) and build a churn prediction framework to identify students at risk based on their activity record. 

The data I used is aggregated from a series of courses offered by Harvard and MIT on *edX* platform. The code and graphs are in two IPython notebooks:

**DataPreparation** For data cleaning, adding new features to existing ones and some exploratory analysis in order to prepare data for modelling. 

**Learning** Starting with imputation of missing data and turning cathegoricals into numericals, the churn predictor is built and applied to the cleaned data (tested/validated). The unbalanced nature of data is addressed by bootstrapping and setting class weights inversely proportional to class frequencies. The efficiency of various churn predictors is gauged by constructing confusion matrices. 
