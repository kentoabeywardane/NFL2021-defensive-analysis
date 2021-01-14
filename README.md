# The Art of Holding a Lead

### NFL 2021 Defensive Analysis (Kaggle)
#### By Kento Abeywardane and Matt Paull
###### https://www.kaggle.com/matthewpaull/the-art-of-holding-a-lead
#
##### Objective
Our objective was to analyze defensive trends towards the end of the game. Specifically we thought it would be 
interesting to look at situations where a team is leading by 4-8 points with 4 minutes or less left in the fourth 
quarter. Our goal was to find defensive trends that contributed to a win.

###
##### Source
The project was done for the NFL Big Data Bowl 2021 on Kaggle where contestants were asked to help evaluate defensive 
performance on passing plays. The overview of this competition, as well as data needed and rules, can be found at: 
https://www.kaggle.com/c/nfl-big-data-bowl-2021. The csv files "games.csv", "plays.csv.zip", "players.csv" in this 
repository can be found on the Data Bowl website.

###
##### Method and Findings
We split up the data between the teams that held their 4-8 point lead to win the game and the teams that blew the lead 
to lose the game. Then looking at the number of pass rushers from both situations we found that the teams who held their
lead used an average of 3.95 pass rushers during their lead within the last 4 minutes, while the teams that blew the 
lead used an average of 4.12 pass rushers.

When comparing the same teams defense from the rest of the game we found the average number of pass rushers before 4 
minutes left was 4.07 for the teams that held their lead, and 4.1 for the the teams that blew their lead. While these 
are essentually equal, it is interesting to see that the teams who blew their lead tended to slightly increase their 
pass rush, while the teams who kept their lead to win tended to slightly decrease their pass rush. We found a similar 
trend for the number of defenders in the box as well.

Next we ran a two-sample T test on the number of pass rushers for the teams who held and blew their leads with under 4 
minutes left in the game and got a P-value of 0.17. Since this is a very specific situation we only found 77 games that 
met our criteria, therefore if this same analysis was run over several seasons to gather more data it might be possible 
to find data with significance.

###
##### Conclusion
Based off of our analysis, we would reccomend to teams who are leading by 4-8 points towards the end of the game that 
they should tend towards a consevative pass rush to win the game.