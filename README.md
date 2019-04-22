# Tools2_Final-Project
Final Project repository for data science 2
# Team Member:
Kaixin Chen  
Ruiwen Jin
# Problems/Motivation
Based on Indeed.com, predict the salary user could get based on their skills in computer science field in Colorado.
# What libraries/tools you will need. What you already know and what else you need to evaluate 
numpy, sklearn,word2vec
# Data Collection details.
Collect the skills required for each job on Indeed.com and the salary the job would pay then store them in an list. Since there is a lot skills we may need do classification on skills as well using the word2vec model.
# Required work detail before build model(clean up, hypothesis, data bias analysis etc.).
Cleaning Meta data scrapped from Steam comment page. Hypothesis is the more skills user mastered, the more salary one would get.
# What is the predictive task and model detail. Model evaluation and selection strategy.
Allow user to enter all the skills he has into our model and predict the salary he could get. We would use regression predictive model for this process.
# How a user is going to test the final model. is there any webpage/command line interface. It can be like using curl from command line and calling a function(lambda via API gateway) in the cloud(AWS).
We will build a webpage on AWS to allow user using our model.
# Tentative time line of activities.
4/25：Finish Dataset collection(include cleaning)  
5/10 Finish Model Building  
6/1: Finish the Project  
