# Data Visualization - Communicating the Findings - Indian Premier League (IPL)
## by (Meghashyamnaidu Bone)


## Dataset

> The dataset consists of the Indian Premier League is a professional Twenty20 cricket league matches information happened in India from the years between 2008 to 2017

> The dataset can be download at the URL https://www.kaggle.com/manasgarg/ipl#matches.csv

> The shape of the dataset is (636, 18)

> I have decided to drop the columns umpire3, id as these are not much helpful for the analysis and I have also decided to delete date to make the data tidy.

> The city, winner, player_of_match, umpire1, umpire2 has missing values in them and considerably the numbers are small, so I chose to delete the rows with missing values.

> In this analysis, I have decided to explore the features including toss_winner, toss_decision, result, dl_applied, winner, win_by_runs, win_by_wickets, player_of_match,venue.


## Summary of Findings

> The highest t-20 IPL matches happened in the year of 2013 and least are in the year of 2014.

> Mumbai Indians is looking like dominant team and where as Rising Pune Supergiant is the team with least wins.

> M Chinnaswamy Stadium has hosted most number of matches and the Vidarbha Cricket Associationn Stadium, Jamntha has conducted least number of matches.

> It's obvious that usually very ocassionally match conduct by DLS method due to the raining conditions.

> Most of the times, the teams chased the scored with 7 wickets in hand.

> Mumbai Indians won the toss most of the times and Rising Pune Supergiant won the toss least number of times.


## Key Insights for Presentation


> The distribution of the feature won_the_run has a right skewed distribution and most of the times the teams wins with < 40 runs difference.

> CH Gayle, YK Pathan, DA Warner, AB de Villiers and RG Sharma are the most top 5 most valueble player and I have made this decision on the basis of number of the player_of_the_match

> Mumbai Indians is looking dominant team and where as Rising Pune Supergiant is the team with least wins.

> There is huge variation for the team Rising Pune Supergiants in number of wickets left after winning where as Gujarat Lions has the least.