# Challenge2
## Background
This repo contains Flask API endpoints for the StackOverflow-Lite project

## Description of Task to be completed:<br/>
Setup and test API endpoints that do the following using data structures
    - Get all questions.
    - Get a question.
    - Post a question.
    - Post an answer to a question.

## How to manually test<br/>

1. Set up a virtual environment<br/>
       ```$ pip install virtualenv```<br/>
       ```$ virtualenv -p python3 myenv```<br/>
       ```$ source myenv/Scripts/activate```<br/>

2. Install Flask<br/>
       ```$ pip install flask```<br/>

3. Clone this repository: <br/>
     ```$ git clone https://github.com/ima254/challenge2/```

4. Run the app: <br/>
     ```python app.py```


EndPoint | Functionality
------------ | -------------
GET /questions | Fetch all questions
GET /questions/<questionId> | Fetch a specific question
POST /questions | Add a question
POST /questions/<questionId>/answers | Add an answer

5. Test the app: 
     ```python test_app.py```
