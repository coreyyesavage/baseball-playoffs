[baseball_playoffs.pdf](https://github.com/coreyyesavage/baseball-playoffs/files/6184738/baseball_playoffs.pdf)
# baseball-playoffs
Can stats tell us which teams will make the MLB playoffs?

## Technology
Jupyter Notebook

## Introduction
Every year 30 Major League Baseball (MLB) teams set out with hopes to make the playoffs. The beginning of a new season brings excitement and hope for both teams and fans. With only 10 teams making the playoffs each year, a lot of those hopes and dreams will be crushed. The Major League season consists of 162 games that span 7 months. Over that time, statistics really start to add up. With so many different statistics being recorded, it is not hard to see why those stats should be analyzed. If this analysis can be used to predict future results, it can completely change the way the game is played or how teams are constructed. This specific idea started to happen in the early 2000s when Billy Beane was running the Oakland Athletics. Billy’s number-based approach completely changed his team and eventually Major League Baseball.


## Data Description
The dataset used in this analysis was taken from the website www.kaggle.com. The data is compiled on Kaggle, while it is gathered from www.baseball-reference.com. The set contains 1232 rows (instances) and 12 columns (attributes).

<img width="653" alt="image" src="https://user-images.githubusercontent.com/60716763/112930047-97968000-90e7-11eb-8d8e-fbee44ab02e0.png">


Table 1 gives the reader a look into the makeup of each instance. Each instance represents a specific team for a specific year and gives attributes that describe statistics from that year. The name attribute represents each of the 30 different teams and each team is represented by a three-letter team abbreviation. The league attribute is represented by either National or American League, as MLB is divided into two leagues. The year attribute represents each season for each team. The fourth and fifth attributes are Runs Scored (RS) and Runs Allowed (RA). They represent the total number of runs scored and runs allowed for each team for each season. The sixth attribute is wins, which represents how many games that team won in that specific year. The seventh attribute is On-Base Percentage (OBP) which measures how often a player reaches base. OBP is equal to the number of times a player reaches base divided by the number of plate appearances. The eighth attribute is Slugging Percentage (SLG). Slugging percentage is calculated by counting up the total number of bases a player reaches divided by number of at-bats. For instances, a single would count as one base, a double as two bases, a triple as three bases, and a homerun as four bases. The ninth attribute is Batting Average (BA). Batting average represents the number of hits divided by the number of at- bats. The G attribute represents the total number of games played for a specific team during that season. The number of games has changed throughout the years that make up this data set. The current major league season
stands at 162 games a season. The final two attributes are Opponent On-Base Percentage Slugging Percentage (OSLG).

## Results

<img width="987" alt="image" src="https://user-images.githubusercontent.com/60716763/113079944-fe796f00-91a3-11eb-87a6-1d2ebfa0271c.png">

Data Description Chart


<img width="714" alt="image" src="https://user-images.githubusercontent.com/60716763/113083177-b8bfa500-91a9-11eb-9fdb-1572d170e122.png">

<img width="345" alt="image" src="https://user-images.githubusercontent.com/60716763/113085459-d7c03600-91ad-11eb-84fb-dd4fff05d295.png">
 
Our analysis brings about a number of different interesting insights.  Insights that should be able to offer teams some guidance on how to construct teams.  For the longest time, teams have always been built around players that hit the most home runs or had the most runs batted in, but this new analytical approach has really started to take off the last two decades.  

Looking through the correlation charts/heat map, we see a number of expected and unexpected trends:
* Out of all of the categories, wins show the strongest correlation (0.616757) with making the playoffs.  Wins being the strongest correlation seems to be pretty straight forward since making the playoffs is all about the teams with the most wins. Looking at the numbers however, it seems that the correlation would be higher. We must realize that the wins column only takes into account wins for specific teams, not the wins of other teams.  The amount of wins you need is relative based on other teams in your league, so teams need to be able to adjust their projections while the season plays out. While setting a goal at the beginning of the year to win a certain amount of games might lead to a playoff berth, it does not guarantee it.  One year 90 wins might get you into the playoffs, the next year it might keep you sitting at home. 
* After wins, the second strongest correlation (0.581094) with making the playoffs is Runs +/-.  Runs +/- is the number of runs scored minus the number of runs against, showing the differential for the year.  Again, this is another trend that seems pretty straight forward.  The greater your run differential, the greater your chances are for winning more games (0.937851 correlation).  The more games you win, the greater your chance of making the playoffs.  While this might not offer a lot of new insights, digging a little deeper into runs does.   When you look at runs scored versus runs against, there is a difference.  RA (-0.532394) shows a stronger correlation with wins than RS (0.511745), meaning that it is more important to prevent runs than score runs.  Good pitching is more valuable than good hitting.  
* There are 3 main batting statistics that rule baseball: batting average (BA), on-base percentage (OBP) and slugging percentage (SLG).  For the longest time, batting average was the statistic that was looked at as the most important.  It was all about getting hits.  Batting average was always the statistic that was talked bout, while on-base percentage and slugging percentage were often overlooked.  As we start to analyze the data, we see a different story.  Out of the 3 batting statistics (BA, OBP, and SLG), OBP shows the strongest correlation with making the playoffs (0.363890) and wins (0.481836).  This means that teams should focus more on a player’s ability to get on base than how they are get on base.  Building a team that has a high OBP gives you the best chances of making the playoffs.  While players that find unconventional ways to get on base (walks, hit by pitch, forcing errors) might not be the most appealing, it should be if you want to win.  Too many times the focus is on hitting homeruns and scoring with one swing of the bat, but the focus really needs to be on getting on base.  The more players get on base, the greater the chance of making things happen. 



## Resources
[1]"Moneyball",Kaggle.com, 2020. [Online]. Available: https://www.kaggle.com/wduckett/moneyball-mlb-stats-19622012. [Accessed: 17- Jun- 2020].
