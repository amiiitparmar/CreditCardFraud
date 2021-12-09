
# Credit Card Fraud Detection using machine learning
This project is all about detecting fraudulent trasaction that are done through credit cards. I have created a machine learning web app which will take some details of transaction from the user and based on that our model will predict whether the transaction is fraudulent or not.
## Problem Statement

Fraud detection is a set of activities undertaken to prevent money or property from
being obtained through false pretenses. Fraud detection is applied to many industries
such as banking or insurance. In banking, fraud may include forging checks or using
stolen credit cards. With the increase in digitalization, there is also increase in the fraudulent activities
happening in various domains, mainly in the retail domain. These are detrimental to the
ecosystem of online transactions.

## Authors

- [Amit Parmar](https://github.com/amiiitparmar)

  
## Proposed Solution


To recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase with the help of Machine Learning.

  
## Features

- Manual insection if fraud is identified
- Detection of upocoming frauds
- Gives better insight  of customer base.
- Prevents customer from falling on fraud traps.

  
## Dataset

The dataset is taken from a kaggle problem statement.
You can downlaod the dataset from [here](https://www.kaggle.com/mlg-ulb/creditcardfraud)

  ## Approach

- Data Exploration : Exploring dataset using pandas,numpy,matplotlib and seaborn.
- Data visualization : Ploted graphs to get insights about dependend and independed variables.
- Feature Engineering : Removed missing values and created new features as per insights.
- Feature Selection : Removed all the unwanted feature using selectKbest.
- Model Selection I : Tested all base models to check the base accuracy. Also ploted and calculate Performance Metrics to check whether a model is a good fit or not.
- Pickle File : Selected model as per best accuracy and created pickle file using pickle library.
- Webpage & deployment : Created a webform that takes all the necessary inputs from user and shows output.

## Technologies Used

- Pycharm Is Used For IDE.
- For Visualization Of The Plots Matplotlib , Seaborn Are Used.
- AWS and Heroku is Used For Model Deployment.
- Mongodb Database is used as Database.
- Front End Deployment Is Done Using HTML , CSS.
- Flask is for creating the application server and pages.
- Git Hub Is Used As A Version Control System.
- os is used for creating and deleting folders.
- csv is used for creating .csv format file.
- numpy is for arrays computations and mathematical operations
- pandas is for Manipulation and wrangling structured data
- scikit-learn is used for machine learning tool kit
- Logistic Regression is used for training the model.
- pickle is used for saving model.

  
## UserInterface

- Home Page
  ![Screenshot (65)](https://user-images.githubusercontent.com/66490787/134642251-4598e41d-ea87-4d53-97b0-6ef51a3b500b.png)


- Prediction page
  
![Screenshot (62)](https://user-images.githubusercontent.com/66490787/134642300-c6ddd820-bde2-414e-a17f-90b5e6cc19fc.png)

![Screenshot (61)](https://user-images.githubusercontent.com/66490787/134642319-594fe3fc-6d11-4717-8834-96575f057d09.png)


## Deployment Link

https://credit-card-fraud21.herokuapp.com/


## Run Locally

- clone the project

```bash
  https://github.com/amiiitparmar/FraudDetection.git
```
- traverse to project directory
```bash
  cd FraudDetection
```
- Install dependencies
```bash
  pip install requirements.txt
```
- Run the app.py
```bash
  python app.py
```

## Support
For support , email @ amiitparmar21@gmail.com








