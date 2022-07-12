<h2> <p align="center">Customer Churn Prediction Using Machine Learning </p> </h2>
<h4> <p align="center">This is a joint project by <a href="https://github.com/KristofVandewynckel"> Kristof Vandewynckel </a> and <a href="https://github.com/Len-Fid"> Yelena Fidrmuc </a> at <a href="https://github.com/becodeorg"><strong>BeCode Ghent </strong></a> <h4>
  <p align = "center">
  <img src="https://strikedeck.com/wp-content/uploads/2016/06/churn.png" alt="Churn" width="500" height="200"/>

## Project  description:
**In this project we are predicticting the customer churn rate - the percentage of customers who either cancel or don't renew their subscription. It is an important measure that can help businesses to retain their clients.**
    
* <a href="https://www.kaggle.com/datasets/blastchar/telco-customer-churn"><strong>Data source </strong></a> - This Kaggle dataset tracks a telco company's customer churn based on a variety of possible factors.
    * **Target** value is churn - it indicates whether or not the customer left within the last month
    * **Features** include: customerID, gender, SeniorCitizen, Partner, Dependents, tenure, PhoneService, MultipleLines, InternetService, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies, Contract, PaperlessBilling, PaymentMethod, MonthlyCharges, TotalCharges
   
## Steps of the project: 
* Exploring and pre-processing the data (Pandas,Numpy)
* Visualising (Matplotlib, Seaborn, Plotly)
* Comparing performance of various ML models (Sklearn)
* Fine tuning the best performing models (Sklearn)
* Looking for clusters in the data (Sklearn)
* Interpreting the results (Sklearn)
    
    
## Machine Learning approach:
  **Overview of the models we tested:**
    
  <img src="https://raw.githubusercontent.com/KristofVandewynckel/Telecom_Churn/main/assets/models.JPG" alt="models" width="350" height="400"/>

    
    
## Visuals: 
  <img src="https://raw.githubusercontent.com/KristofVandewynckel/Telecom_Churn/main/assets/gender.png" alt="Churn" width="500" height="450"/>
  <img src="https://raw.githubusercontent.com/KristofVandewynckel/Telecom_Churn/main/assets/monthly_charges.png" alt="Churn" width="500" height="450"/>
  <img src="https://raw.githubusercontent.com/KristofVandewynckel/Telecom_Churn/main/assets/internet_connection.png" alt="Churn" width="500" height="450"/>
  
## Overview of the clusters.

In this unsupervised way of machine learning, we take away the target column (churn? yes/no) from the database and use Kmeans clustering to let the algorithm decide for itself which customers share certain patterns.
  <img src="https://raw.githubusercontent.com/KristofVandewynckel/Telecom_Churn/main/assets/clusters.png" alt="Churn" width="500" height="450"/>
## ROC Curve
  <img src="https://raw.githubusercontent.com/KristofVandewynckel/Telecom_Churn/main/assets/roc.JPG" alt="ROC" width="500" height="400"/>
    
## Odds and Probabilities

Here we have an overview of how certain featues impact the chance of churning. 
  <img src="https://raw.githubusercontent.com/KristofVandewynckel/Telecom_Churn/main/assets/unknown.png" alt="Churn" width="500" height="600"/>

  
  
