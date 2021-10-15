#  NBA Project Assessment 

![logo]( https://github.com/teao11/barca_fc_basketball_capstone/blob/main/Images/NBALogo.png)

### 🏀 Self-Assessment
-----------------------

The topic we picked for our Final Project was 'Predicting NBA Championships'. When we started this project I was not familiar with the metrics used in the game. My knowledge was limited to the basic rules and guidelines. But with the help of my team - I am now familiar with assists, rebounds, RAPTOR scores etc. My primary contribution to the team was to identify data sources which could help our analysis. I also was responsible to set-up and maintain the Postgre SQL database, and set-up the AWS RDS interface to share the database with other team members.I also created an ERD diagram to help set-up the SQL tables.

These database tables and data was used by the team for our Machine Learning model. I was also responsible to create our Tableau Public Storyboard and integrate the different components that each tema member had worked on. 

### 🏀 Team Assessment  
------------------------
⛹️‍
The team members were extremely knowledgable on NBA stats, and were able to direct me on each steps. We used our personal Zoom meeting links to meet outside bootcamp hours and co-ordinated on our project submissions and data clean-ups. Doubts and conerns were raised and were looked into and cleared as a team during these meets.

Time was the main contstraint - with all of us having regular daytime jobs made it difficult to co-ordinate the meetings and work. Luckily we had some smart team members who did a great job on extracting the data and modelling it for purposes.

To future bootcamp members - my suggestion would be to pick the topic and the teams early on in the project so that they can get an early start. We lost some precious time in the beginning of the project getting to know each other and come-up with a topic.

### 🏀 Summary of Project 
----------------------------

With the 2021-2022 NBA season upon us, our team has decided to analyze NBA data to determine what makes a championship team. We aim to identify key factors of past teams to help predict this upcoming season's champion.

Below are the questions we hope to answer with the data:

* What makes a NBA team successful?
* What are the key factors to create a NBA championship team?
* Can we predict who is going to win this upcoming season?

We picked the top 2 wins and top 2 losses by the team, and used them as our features. Target would be Win or Loose.

This are our model's output summary:

#### Accuracy Score : 0.8235294117647058
#### Classification Report
####              precision    recall  f1-score   support

####         0.0       0.87      0.93      0.90        14
####         1.0       0.50      0.33      0.40         3

Our model is better trained to predict the losing team more than the winner 😄
