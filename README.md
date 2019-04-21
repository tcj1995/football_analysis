# Prediction for the Premier League

# Team member : 
Chuanjie Tang; Tong Wu

# Problems:
Based on the Football data for England (and Wales) incl. English Premier League from 2010 to 2018, we want to predict the results in the next years.

# Data Collection details:
https://github.com/footballcsv/eng-england/tree/master/2010s

# What libraries/tools you will need:
We will build a simple Poisson model to predict the results of English Premier League matches. 
Maybe more tools will be used when we are going to expand that project.

# Any Literature review:
https://dashee87.github.io/football/python/predicting-football-results-with-statistical-modelling

"Football (or soccer to my American readers) is full of clichés: “It’s a game of two halves”, “taking it one game at a time” and “Liverpool have failed to win the Premier League”. You’re less likely to hear “Treating the number of goals scored by each team as independent Poisson processes, statistical modelling suggests that the home team have a 60% chance of winning today”. But this is actually a bit of cliché too (it has been discussed here, here, here, here and particularly well here). As we’ll discover, a simple Poisson model is, well, overly simplistic. But it’s a good starting point and a nice intuitive way to learn about statistical modelling. So, if you came here looking to make money, I hear this guy makes ￡5000 per month without leaving the house."


# Required work detail before build model(clean up, hypothesis, data bias analysis etc.):
clean up:collect and summary the information of every team in the seven years from the raw data.

# What is the predictive task and model detail. Model evaluation and selection strategy.
predictive task: the net difference; points and top three 

model details:The model is founded on the number of goals scored/conceded by each team. Teams that have been higher scorers in the past have a greater likelihood of scoring goals in the future. We’ll import all match results from the recently concluded seven Premier League seasons.

# how a user is going to test the final model. is there any webpage/command line interface. It can be like using curl from command line and calling a function(lambda via API gateway) in the cloud(AWS).
We decide to put the model in the webpage for the users to test.

# Tentative time line of activities:
Steps and Outlines: Roughly Time Estimate

Data Cleanup: two weeks 

transformation: one week

feature engineering: several days

statistical summary: one week

visualization: three weeks
