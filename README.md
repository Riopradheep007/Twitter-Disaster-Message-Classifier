# Twitter-Disaster-Message-Classifier

## Table of content
   - Overview
   - Motivation
   - Technical Aspect
   - Installation
   - Run
   - Directory Tree
   - Technologies Used
   - credits
## Demo
#### Link: https://disaster-message-classifiers.herokuapp.com/
![Screenshot from 2020-07-23 12-18-22](https://user-images.githubusercontent.com/46066018/88258887-cea5cd80-ccde-11ea-8a2f-bc9d7cbcee4f.png)

### Overview
   This is a Twitter Disaster Message Classifier Flaskapp this was a machine learning model takes input as a text and predict output the user entered Tweets is a **Emergency** Tweets or **Not**
   
### Motivation

In this pandemic situation i was decide to learn Flask web app.Why i was interested to learning flask is because you know when ever we are creating a Machine Learning model or deep learning model after that we have to deliver project to our client, the project should be easily accessible by people for that we need  a user interface thats why i was started Flask, for the hands on experence i took the project in kaggle.


### Technical Aspect
   1. Training the model using machine learning.
   
   2. The text data eas cleaned using NLTK Library.
       - User have to enter their message in the text area.
       - After entered the text my model will predict the user is in Emergency situation are not.
       
### Installation
The Code is written in Python 3.7. If you don't have Python installed you can find it [here](https://www.python.org/downloads/). If you are using a lower version of Python you can upgrade using the pip package, ensuring you have the latest version of pip. To install the required packages and libraries, run this command.

    pip install -r requirements.txt
    
### Run
Torun this model In Linux/Mac open Terminal.If you are Windows user open your command prompt.Run the command 

    python app.py
    
    
### Directory Tree
      ├── Dataset
      │   ├── sample_submission.csv
      │   ├── test.csv
      │   ├── train.csv
      │   
      ├── static
      │   ├──style.css
      ├── templates
      │   ├── result.html
      |   ├── home.html
      ├── README.md
      ├── Twitter Disaster Message Classifier.ipynb
      ├── app.py
      ├── classifier.pkl
      ├── cvx.transform1.pkl
      ├── requirements.txt
      
  
 ### Technologies Used
 
 ![flask ](https://user-images.githubusercontent.com/46066018/88272584-914d3a00-ccf6-11ea-9fc0-91d97930dd5b.png)
 ![images (1)](https://user-images.githubusercontent.com/46066018/88272969-1fc1bb80-ccf7-11ea-845f-1cffd4b912ca.png)
 
### Credits

[Kaggle](https://www.kaggle.com/) - This project wouldn't have been possible without  Kaggle dataset.
