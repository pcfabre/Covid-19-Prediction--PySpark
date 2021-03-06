# Files organization of our Project: COVID-19 with Spark (Databricks)



## How this project has been carried out?

We used a dataset from kaggle website (https://www.kaggle.com/sudalairajkumar/novel-corona-virus-2019-dataset/discussion?fbclid=IwAR2yuD9I4j5UBNK8rd-VXYYSKSFylH-voiZrSUkiL6X90GUyum841UpK2_s) recorded mainly from the beginning of the disease to end 
of March 2020. The objective of this project is to predict if a person is going to be infected (modality sick), then will he/she
recover or die?
Our data contain information on the person (gender, age, living location), on the symptoms & on the country. 
Some of the problems we have encountered during this project are for example the presence of missing values and how to replace them.
Finally, the problem we estimated is a multinomial classification problem.


## Major steps:

1-data cleaning & preprocessing: data types, deleting special characters from text data, conversion to lowercase, eliminate trailing
spaces, treatment of missing values & tf-idf.

2-data analyses: variables visualization & analysis of correlations

3-Prediction models: estimate a random forest & Naive Bayes classifiers (The random forest method reveals to be the best in this case!!)

4-parameters tuning: using scikit-learn & RDD 


## Additional output: 

creation of a dashboard with Databricks


## How to run the notebooks ?

You need first to run the notebook Project_COVID_19_final.ipynb (at least till the end of the Data Analysis part)
before running Dashboard_creation.ipynb 
Link for the dashboard: file:///C:/Disque%20docs/M2%20Econometrics%20and%20applied%20statistics/courses_sem2/Big%20Data/Project_COVID19/class-project-covid_19-master/Dashboard.html
