# ML-Observability---Drift-report-with-feature-importance-enabled

# Data Drift 
Data drift is a change in the statistical properties and characteristics of the input data. It occurs when a machine learning model is in production, as the data it encounters deviates from the data the model was initially trained on or earlier production data.This shift in input data distribution can lead to a decline in the model's performance. The reason is, when you create a machine learning model, you can expect it to perform well on data similar to the data used to train it. However, it might struggle to make accurate predictions or decisions if the data keeps changing and the model cannot generalize beyond what it has seen in training.

Hence it very important to track data drift at feature level for different periods of data like the reference period and current period . In this example we are comparing feature drift between different periods and also mapping them based on feature importance

# Steps of Implementation : 

## Step 1 : Import necessary libaries

## Step 2 : Prepare the dataset ( both the reference and current period )

## Step 3 : Create a baseline RandomForest regressor model 

## Step 4 : Drift analysis with feature importance highlighted : default version

Visual representation , the detailed report is attached as report.html , download and open in any browser of choice

![image](https://github.com/user-attachments/assets/b6a8961e-55d5-4f2a-9292-0da999dbfa9e)

## Step 5 : Drift analysis with importances : custom importance

Visual representation , the detailed report is attached as report_v1.html , download and open in any browser of choice

![image](https://github.com/user-attachments/assets/802ab293-5a80-41cc-a6a9-4c4e8fdad515)

Happy coding :)



