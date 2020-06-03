# Capstone Project 2: Bar Crawl

This project is currently in progress. Come back later for updates!

The aim of this project is to predict whether an individual is drunk based on their movement. The primary datasets used are TAC (transdermal alcohol content, similar to BAC) readings and 3-axis accelerometer data for each of 13 participants in this study. Variance in movement over 10-minute windows using the accelerometer data is calculated, the idea being that a drunk person will be less steady on their feet and therefore have more variance in movement. Variance data is then combined with TAC Readings in order to determine if someone is drunk. Finally, a machine learning model is constructed with variance in 3 axes as features and whether the label of "drunk" as the target variable.

This folder contains the preliminary code, the final code, and project reports.

You can also find some of the original datasets here. This includes both the raw and clean versions of the TAC Readings, as well as the phone type of every participant. Unfortunately, the original accelerometer data is too large for GitHub. However, you can find it at the following link, along with a report on the original study which produced the datasets used here: https://archive.ics.uci.edu/ml/datasets/Bar+Crawl%3A+Detecting+Heavy+Drinking

I've also included a hyperparameter table of models used in the final project, called 'model_table_9.csv'. 

Those who are interested in learning more about the project can check out my final report:
https://github.com/mdubow/Data-Science-Portfolio/blob/master/Capstone-Project-2/Reports/Final%20Report/Capstone%202_%20Final%20Report.pdf
