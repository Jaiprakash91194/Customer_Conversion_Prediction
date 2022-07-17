
# GUVICARE:
<img align = right height = 120 width = 120 src = https://github.com/Jaiprakash91194/Customer_Conversion_Prediction/blob/main/GUVI_logo3.png>

GUVICARE - Application to predicts whether a customer will opt for an insurance policy.

![Random GIF](https://c.tenor.com/b5J9lCPQlAEAAAAi/democracyrising-our-time-now-for-our-health.gif)
## Description:

GUVICARE is an application can predict whether the customer will opt for insurance plan based on various features taken into consideration.
The Model will analyse the parameters provided by user and predict whether customer taken insurance plan.

## Detailed Description:
<img align = right height = 120 width = 120 src = https://github.com/Jaiprakash91194/Customer_Conversion_Prediction/blob/main/GUVI_Logo.png>

This is a real world Datascience problem, given in DATATHAON1.0(30 hours live hackathon event), an itiative by GUVI to get the students get exposure to real world datascience problems, conducted on 16&17 July 2022.

Participants are provided with real world datascience problems and are expected to create solution to problem using Datascience techniques.

We are aware that health insurance is  compulsary for all individuals. But due to verious factors, people skip their insurance plans, although various attempts/techiniques are followed by insurance providers.

We are provided with historic data of customer conversion to Insurance plans. 
As a datascientist, we need to gather insights from the data and suggest on business decision/techiniques to be followed to increase the conversion rate.
In this Classification task, we build an ML model that will predict if a client will subscribe to the insurance, based on certain parameters as an input.


## DataSets:

**Input Features:**

- age (numeric)
- job : type of job
- marital : marital status
- educational_qual : education status
- call_type : contact communication type
- day: last contact day of the month (numeric)
- mon: last contact month of year
- dur: last contact duration, in seconds (numeric)
- num_calls: number of contacts performed during this campaign and for this client
- prev_outcome: outcome of the previous marketing campaign (categorical: "unknown","other","failure","success")

**Output variable (desired target):**

- y --> has the client subscribed to the insurance?(YES/NO)
## Methods Used:
- Exploratory Data Analysis (EDA)
- Data Collection
- Data Cleaning
- Feature Engineering
- Modelling
- Render application online
## Technologies used
- Python
- Machine Learning
- Pandas, matplotlib
- seaborn, Google Colab
- flask, flasgger
## ML Algorithms Used
- RandomForestClassifier
- LogisticRegression
- AdaBoostClassifier
- KNeighborsClassifier
- GaussianNB
## Performance Evaluation

Below are the evaluation metrics used for calculating the Performance of model:
- Confusion Matrix
- Accuracy Score
- ROC Accuracy Score

## Conclusion

We select the best model for prediction the output, based on model performance for the datasets provided.

## Application

Once we select the best model, we use FLASK to host the application.
The application takes various input from user and predicts whether the customer will opt to insurance plan or not.

## Flask API output
 - ![FLASK API Screenshot](https://github.com/Jaiprakash91194/Customer_Conversion_Prediction/blob/main/Customer_Prediction_snip.jpg "FLASK API Output")

