# CIS Fraud Detection

### Requirements
* Python 3.10

### Run instructions
* Create a new pipenv environment using command ```pipenv shell```
* Install dependencies using ```pipenv install```
* Create data folder inside project and add [datasets](https://www.kaggle.com/competitions/ieee-fraud-detection/data) from kaggle 
* Create models folder inside project
* Run EDA.ipynb to generate feather files with the datasets
* Run FE to save the dataset that was feature engineered
* Run one of the two models: XGBoost or LightGBM
