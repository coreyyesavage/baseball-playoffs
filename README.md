[baseball_playoffs.pdf](https://github.com/coreyyesavage/baseball-playoffs/files/6184738/baseball_playoffs.pdf)
# baseball-playoffs
Can stats tell us which teams will make the MLB playoffs?

## INTRODUCTION
Every year 30 Major League Baseball (MLB) teams set out with hopes to make the playoffs. The beginning of a new season brings excitement and hope for both teams and fans. With only 10 teams making the playoffs each year, a lot of those hopes and dreams will be crushed.
The Major League season consists of 162 games that span 7 months. Over that time, statistics really start to add up. With so many different statistics being recorded, it is not hard to see why those stats should be analyzed. If this analysis can be used to predict future results, it can completely change the way the game is played or how teams are constructed. This specific idea started to happen in the early 2000s when Billy Beane was running the Oakland Athletics. Billy’s number-based approach completely changed his team and eventually Major League Baseball.

## Data Description
The dataset used in this analysis was taken from the website www.kaggle.com. The data is compiled on Kaggle, while it is gathered from www.baseball-reference.com. The set contains 1232 rows (instances) and 12 columns (attributes).

<img width="653" alt="image" src="https://user-images.githubusercontent.com/60716763/112930047-97968000-90e7-11eb-8d8e-fbee44ab02e0.png">


Table 1 gives the reader a look into the makeup of each instance. Each instance represents a specific team for a specific year and gives attributes that describe statistics from that year. The name attribute represents each of the 30 different teams and each team is represented by a three-letter team abbreviation. The league attribute is represented by either National or American League, as MLB is divided into two leagues. The year attribute represents each season for each team. The fourth and fifth attributes are Runs Scored (RS) and Runs Allowed (RA). They represent the total number of runs scored and runs allowed for each team for each season. The sixth attribute is wins, which represents how many games that team won in that specific year. The seventh attribute is On-Base Percentage (OBP) which measures how often a player reaches base. OBP is equal to the number of times a player reaches base divided by the number of plate appearances. The eighth attribute is Slugging Percentage (SLG). Slugging percentage is calculated by counting up the total number of bases a player reaches divided by number of at-bats. For instances, a single would count as one base, a double as two bases, a triple as three bases, and a homerun as four bases. The ninth attribute is Batting Average (BA). Batting average represents the number of hits divided by the number of at- bats. The G attribute represents the total number of games played for a specific team during that season. The number of games has changed throughout the years that make up this data set. The current major league season
stands at 162 games a season. The final two attributes are Opponent On-Base Percentage Slugging Percentage (OSLG).
