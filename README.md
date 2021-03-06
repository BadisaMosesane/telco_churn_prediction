**Telco Customer Churn Prediction**

Customer attrition, also known as customer churn, customer turnover, or customer defection, is the loss of clients or customers. This application allows you to predict telco customer churn using machine learning algorithms (SVM, XGBoost) using Dash - an open source Python framework for building web analytic applications.

The project is Powered by the SAIS Universities-Industry-Government Co-creation Platform:  
![](images/UIG_logo.png)

SAIS-UIG - a project that aims  to  develop  a  universities  centric  co-creation  platform  with  its  associated   activities,   government   &   industry   partnerships,   mentorship   and   processes centred on industry and government or stakeholder defined challenges solved by students through well-defined mentored flagstone capstone projects.
[SAIS-UIG](https://www.saisprogramme.org/storage/app/media/projects/Universities%20Industries%20Government.pdf)

**Installation and Usage**

    Install all dependencies listed in requirements.txt, $ pip install -r requirements.txt
    Run app.py to launch a local Dash server to host the Dash app. A link will appear in your console; click this to use the Dash app.

![](images/uig_churn.png)
![](images/churn_app.png)



**Table of Contents**

    Project Analysis
    Installation
    Metric
    File Descriptions
    Results
    Licensing, Authors, and Acknowledgements

**Project Analysis**

Customer attrition, also known as customer churn, customer turnover, or customer defection, is the loss of clients or customers.
![](images/churn.jpeg)

The main contribution of our work is to develop a churn prediction model which assists telecom operators to predict customers who are most likely subject to churn. The model developed in this work uses machine learning techniques on big data platform and builds a new way of features’ engineering and selection.

Predictive analytics use churn prediction models that predict customer churn by assessing their propensity of risk to churn. Since these models generate a small prioritized list of potential defectors, they are effective at focusing customer retention marketing programs on the subset of the customer base who are most vulnerable to churn.
![](images/correlation.png)

![](images/features.png)


**Installation**

The code in this project is written in Python 3.6.6 :: Anaconda custom (64-bit). The following additional libraries have been used:

    pandas
    numpy
    matplotlib
    seaborn
    plotly
    sklearn
    warnings
    time
    graphviz
  

**Metrics**

The following metrics have been used to compare the model performances:

    Accuracy
    Precision
    Recall
    F1 score
    AUC ROC

File Descriptions

The Jupyter notebooks included in this project are:

    Telco Customer Churn Prediction.ipynb.ipynb

Data files (under data directory):

    WA_Fn_UseC_Telco_Customer_Churn.csv

**Results**

The following classifiers have been compared:

    Logistic Regression
    Random Forest
    Decision Tree
    KNN
    

The results achieved the above classifiers give an output of customerID, churn and prediction, with prediction being a probability of how likely a customer is to churn, targeting the customers who haven't churned but are likely to.
![](images/predictions.png)


**Issues**
* improve churn prediction accurary
* train on more data
* deploy application live

**Licensing**
[Apache 2.0](https://www.apache.org/licenses/LICENSE-2.0)

**Authors**
Badisa Mosesane 

**Contributing** 
Send us a PR at https://github.com/BadisaMosesane/telco_churn_prediction
