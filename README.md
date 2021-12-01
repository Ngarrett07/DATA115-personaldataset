# DATA115-personaldataset
comparison of the starting NFL rookie QB, played min 5 games

# Motivation:
This year in the 2021 draft, eight quaterbacks(QBs) were taken in the first three rounds and according to NFL.com this is the most in draft history. With five of the QBs going in the first round and a couple expected to start the season, I wanted to analyze how successful they were compared to others in the draft class. Because many of the general QB stats are inconsistent game to game, I chose to find more advanced stats that were not only more stable by took the current game situation into consideration. My driving questionfor this data set is: How successful and efficient was the QB playing this year?

# Data Sources:
ESPN: https://www.espn.com/nfl/qbr/_/view/weekly 
Pro Football Reference: https://www.pro-football-reference.co

# Data Gathering and Proccessing:
I decided to collect data from the current NFL season. This means every week, there is an increase in data added, and because of the due date of this assignment, I am cutting it off at week 12. For this data set I also chose to only include the stats of the player if they started and played the majority of the game. Wilson and Fields both went out with injury during their games, so those games are not included. For Jones, while he did leave the game early twice it was due to the patritos blowing out their opponent, so he left in the fourth quarter after playing most of the game. I decided to base most of my analysis off of advanced statistics. So I am using the Quarterback Rating (QBR), Expected points added (EPA) and Pass points added (PPA). These numbers I found from https://www.espn.com/nfl/qbr/_/view/weekly for each week. I also wanted to use Adjusted net yards per attempt (ANY/A), because I could not find these numbers for each player for game, I used the formula and plugged the components to this equation in. Those components included touchdowns, interceptions, passes attempted, passing yards, number of times sacked, and sack yards. The numbers for these stats I found from https://www.pro-football-reference.com searching each rookies's name. After compiling all of my data, I created multiple visuals, including scatterplots and boxplots to begin to find any trends in the data. 


# Visualization:
![Rookie's Weekly QB rating so far during the 2021 season](https://raw.githubusercontent.com/Ngarrett07/DATA115-personaldataset/main/Rookies%20QBR%20Weekly.png)

This graph shows the comparison of the rookie QBs and their rating. The QB rating stat measures their efficiency during the game, taking other player's performance and the game state and quality of plays made into consideration. Additonally, this graph shows which weeks the Qb won their game. 

# Analysis
Overall the 2021 QB draft class are having trouble succeeding, combining for a 14-28 record. While it is hard to completely judge these players based on their performance alone and not considering the poor play by surrounding teammates or opponent, it is easy to see that Jones is performing above all others consistently. 
