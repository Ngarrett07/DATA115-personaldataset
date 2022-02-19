# DATA115-personaldataset
comparison of the starting NFL rookie QB, played min 5 games

# Motivation:
This year in the 2021 draft, eight quarterbacks(QBs) were taken in the first three rounds and according to NFL.com this is the most in draft history. With five of the QBs going in the first round and a couple expected to start the season, I wanted to analyze how successful they were compared to others in the draft class. Because many of the general QB stats are inconsistent game to game, I chose to find more advanced stats that were not only more stable but took the current game situation into consideration. My driving question for this data set is: How successful and efficient were the rookie QBs playing this year?

# Data Sources:
ESPN: https://www.espn.com/nfl/qbr/_/view/weekly 
Pro Football Reference: https://www.pro-football-reference.com

# Data Gathering and Processing:
I decided to collect data from the current NFL season. This means every week, there is an increase in data added, and because of the due date of this assignment, I am cutting it off at week 12. For this data set I also chose to only include the stats of the player if they started and played most of the game. Wilson and Fields both went out with injury during their games, so those games are not included. For Jones, while he did leave the game early twice it was due to the Patriots blowing out their opponent, so he left in the fourth quarter after playing most of the game. I decided to base most of my analysis off advanced statistics. So, I am using the Quarterback Rating (QBR), Expected points added (EPA) and Pass points added (PPA). These numbers I found from https://www.espn.com/nfl/qbr/_/view/weekly for each week. I also wanted to use Adjusted net yards per attempt (ANY/A), because I could not find these numbers for each player for game, I used the formula (pass yards + 20*(passingTD) - 45*(interceptionsThrown) - sack yards)/(passing attempts + sacks) and plugged the components to this equation in. Those components included touchdowns, interceptions, passes attempted, passing yards, number of times sacked, and sack yards. The numbers for these stats I found from https://www.pro-football-reference.com searching each rookies’ name. After compiling all my data, I created multiple visuals, including scatterplots and boxplots to begin to find any trends in the data. I compared EPA, QBR and ANY/A each to each other in scatter plots, then the QBR, EPA and ANY.A to week number. For box plots I looked at Rookies’ EPA, QBR and ANY/A. After doing further research and creating graphs, I found EPA and QBR are very closely related, which is why I chose to only include QBR scatter in my visualizations. I also made a bar chart for wins each rookie had to see how they compared to each other.


# Visualization:
![Rookie's Games Won through Week 12](https://raw.githubusercontent.com/Ngarrett07/DATA115-personaldataset/main/RookieWinsUp.png)
This graph shows the comparison of the games each starting rookie has won this season. 

![Rookie's QB rating through Week 12](https://raw.githubusercontent.com/Ngarrett07/DATA115-personaldataset/main/QBRup.png)
This graph weekly performance of the rookie's QBR, average QB is 50. 

![Rookie's Adjusted Net Yards per Attempt through Week 12](https://raw.githubusercontent.com/Ngarrett07/DATA115-personaldataset/main/ANYup.png)
This graph reflects the four major plays a QB can commit, a touchdown, interception and sack and yards completed. The higher the ANY/A is the better. The interceptions are negatively weighted more than a touchdown thrown. 


# Analysis
Overall, the 2021 QB draft class are having trouble succeeding, combining for a 14-28 record. Comparing the two scatterplots of QBR and ANY/A side by side, I was able to determine no player was consistently playing at one level, rather all had fairly large ranges, and Lawrence even had a couple outliers. This inconsistent play can be due to the quality of opponent they are facing, however the graph I chose to use are not able to measure that. Analyzing their efficiency, I considered a higher ANY/A and QBR are more efficient. The players that had a higher ANY/A meant that generally they are passing for more yards and touchdowns while taking less sacks and interceptions. This means they are more successful on the field by committing less mistakes that cost the team. Looking at QBR, which is closely related to EPA, I would expect to see more wins when the QBR is high because the offense is efficiently moving the ball down filed. However, with this QB class there is no set line where the QBR value is closely correlated to a win. The average QB QBR is a 50, so can conclude that Jones and Fields tend to be the most efficient QBs of the draft, regardless of their win status. Lastly, while stats can tell a lot about a player, it is their record that will be the ultimate sign of success because it is the one that matters the most when it comes to playoffs. While it is hard to completely judge these players based on their performance alone and not considering the poor play by surrounding teammates or opponent, it is easy to see that Jones is performing above all others consistently, with the best record and average higher numbers. Fields has been efficient and successful at times, but is also very inconsistent, Wilson and Lawrence have both been inefficient and had limited success. Lastly, Mills has had a few efficient games, but has zero wins and has played inconsistently.

