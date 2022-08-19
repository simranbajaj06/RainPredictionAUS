 
# Rain-Prediction
A project on predicting whether it will rain tomorrow or not by using the Rainfall in Australia dataset
This project is tested over two ml models random forest, logistic regression..
Out of these two  models random forest performed very well giving an AUC score around and ROC score of 88 far better than other.
Here due to my system compatibility is very low. So I havent done hyperparameter tuning. But it is highly recommended to do it if possible.

# Tech Stack
* Front-End: HTML, CSS, Bootstrap
* Back-End: Flask
* IDE: VS code

# How to run this app
* create a Folder on your machine
* Download the .rar files
* Paste the file in the newly created folder
* Install all the packages by using the following command
* pip install -r requirements.txt
* Now. Run the app
* python app.py


# Workflow

# Data Collection: 
[Rainfall Prediction in Australia dataset](https://www.kaggle.com/jsphyg/weather-dataset-rattle-package) from Kaggle
# Data Preprocessing: 
* Missing Values Handled by Random Sample imputation to maintain the variance
* Outliers are handled using IQR and boxplot
*  Imbalanced Dataset was handled using SMOTE
# Model Creation:
* Two Different types of models were tried random forest, logistic regression.
* Out of these two random forest performed well
* The conclusion were made using classification metrics. roc curve and auc score
# Model Deployment
* The model is deployed using Flask 




