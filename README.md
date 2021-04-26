
# Sparkify(Spark Project)

## Project overview
SparkIfy provide music services including free account and premium account, I need to give the company a model which help to identify the customer who potentially cancel the premium service.

## Dataset
There is the full 12GB dataset that provided by Udacity.

## Installation
The code should run using Python version 3.*. 

The necessary libraries are:   pandas,   pyspark,    seaborn,    matplotlib, 

## File Descriptions
README.md  

Sparkify.ipynb  

data\mini_sparkify_event_data.zip  

LICENSE 
## Result


![image](https://user-images.githubusercontent.com/34250620/116113474-8610ab80-a686-11eb-8e23-4a37169c43d2.png)

The final model base on the random forest classifier with num_tree = 10 and new data that the churn label is created by ‘Cancellation Confirmation’ and ‘Downgrade’ actions of ‘page’. The F1-score of model is 0.844754 on test set.

## Medium link
https://xyf3333.medium.com/sparkify-churn-prediction-5ea8ca7b61e7 

## Licensing, Authors, Acknowledgements
The Dataset used in this process is provided by **figure-8** that contains real labeled disaster messages received by an aid organization during disaster events.
