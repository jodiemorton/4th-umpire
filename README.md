# 4th Umpire

This Django and Machine Learning powered Web app predicts and analyse IPL matches. It currently has three working model i.e 
prediction of a match winner before toss, prediction of expected score of 1st inning at any point of time during the match 
and prediction of winner, match concluding over during the 2nd inning of the match.


## Webpage
Live project is available [here](https://fourth-umpire.herokuapp.com).

## Download code here
Facing error  not able to upload in github nvm code is  [here](https://wetransfer.com/downloads/738c861ad5beae825d9f4aa7aecdbc6020201202083052/e059de)

## Local Setup
Create and activate a virtualenv:

```bash
conda create --name myenv
Replace myenv with the environment name.
proceed ([y]/n)?
conda activate myenv
conda install scikit-learn=0.19.2
conda install django
pip install django-bootstrap-form

```
### CHECKOUT THIS
Click [Here](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) for detailed info on setting the env.

Clone the repository on your local environment <br>

```bash
git clone https://github.com/aasis21/4thUmpire.git `
```

Navigate to the folder <br>
```bash 
cd 4thUmpire/web
```

Install the required dependencies <br>
```bash
pip install -r requirements.txt 
```
# More Changes
1. Inside the 4thUmpire\web\fourth_umpire\templates\fourth_umpire folder
2. Try to change the HTML files with {% load static %} instead of {% load staticfiles %}.
3. You are good to go.



Run the localhost-server <br>
```bash 
python manage.py runserver
```

The web-app will be available at `127.0.0.1:8000` on your browser. 

## About
This web-app is created for Microsoft Code Fun Do competition.

- In this project we have use various algorithms like Naive Bayes, SVM, Random Forest  in training our various machine learning models. And on different stages of training and testng, final model works and best fit with random forest algorithm. 

- We have used dataset from Kaggle and then modified the csv files and make various csv files in order to train and for working of our different models.In addition, We have use varoius python libraries such as scikit learn, numpy, pandas,etc in order to code our models. 
