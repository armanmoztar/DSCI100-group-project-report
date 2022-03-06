# DSCI100-group-project-report


#### Introduction
Betting on the outcomes of soccer matches is very common in the sporting community. Based on our dataset, which team is more 
likely to win and what is the given score? This project involves using halftime match statistics to predict the outcome of the 
match, as well as the final score. The given dataset provides specific match information from the 2018-2019 Premier League games
including which teams played, half-time score, shots, shots-on-target, shots that hit woodwork, corner kicks, fouls committed, 
free kicks committed, yellow and red cards given out and more factors affecting the likeliness of a goal. 


#### Method:
We plan on using the following factors to conduct our data analysis:
Chosen Variables/Columns| Justification: 

FTHG and HG = Full Time Home Team Goals
Testing Data: Not used in our predictions
FTAG and AG = Full Time Away Team Goals
Testing Data: Not used in our predictions
FTR and Res = Full Time Result (H=Home Win, D=Draw, A=Away Win)
Testing Data: Not used in our predictions
HTHG = Half Time Home Team Goals
Allows for performance assessment at half time when paired with total attempted team shots.
HTAG = Half Time Away Team Goals


HTR = Half Time Result (H=Home Win, D=Draw, A=Away Win)


HS = Home Team Shots
Combined with total team goals, total team shots allow us to further predict the accuracy of the team at halftime.
AS = Away Team Shots


HST = Home Team Shots on Target
(Shot blocked by opponent’s goalie)
This factor pair gives us an idea of how many times a team got close to the opponent’s net and the effectiveness of their 
opponent’s goalie.
AST = Away Team Shots on Target
(Shot blocked by opponent’s goalie)


HHW = Home Team Hit Woodwork
Alongside HST and AST, these factors show us how many times a team got within shooting distance of the net.
AHW = Away Team Hit Woodwork


HC = Home Team Corners
Shows a team’s accuracy and how often the team reaches the opponent’s goal.
AC = Away Team Corners


HFKC = Home Team Free Kicks Conceded


AFKC = Away Team Free Kicks Conceded


HO = Home Team Offsides
Frequency of fouls and how often the team is around the opponent’s goal
AO = Away Team Offsides




In our data analysis, we plan on visualizing our data using a scatter plot. Using a scatter plot will allow us to better 
understand the correlation between predictors (see list of columns and variables above) and net goal difference.


#### Expected outcomes and significance
In our data analysis, we expect to successfully and accurately find the winner between two teams, alongside the final score. 
These findings could increase the probability of an accurate prediction regarding the outcome of a game between two teams. Our 
analysis can then be used to answer future questions, such as : Which team in a league has the greatest chances of winning for 
the given season?
