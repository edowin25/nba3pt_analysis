## An analysis how the 3 point shot impact the NBA game of basketball

![image](https://github.com/edowin25/nba3pt_analysis/blob/edowin25-patch-2/cover.png?raw=true)

### Brief Introduction
This project analyses how the 3 point shot changes game from season to season. We will look at the following in this project. You can use the table of contents to access the necessary sections for your information. However, for caveat purpose, this analysis mainly looks at the 3 point shots and its correlation to other statistics. Further analysis can be done to see how the 3 point shot affects/is affected by conditioning, imapct on entertainment value etc.

<!-- TABLE OF CONTENTS -->
<details>
  <summary><b>Table of Contents</b></summary>
  <ol>
    <li><a href="#project-context">Project Context</a></li>
    <li><a href="#datasets">Datasets</a></li>
    <li><a href="#lines-of-enquiry">Lines of Enquiry</a></li>
    <li><a href="#chart-examples">Chart Examples</a></li>
  </ol>
</details>

<!-- PROJECT CONTEXT -->
## Project Context
Over the years, we have seen the popularity of the 3 point shot in the game of basketball rise all around us. This whole hype first started out with Stephen Curry, dubbed as the greatest shooter of all times and the Golden State Warriors revolutionalise a new type of offense where it focuses on small ball and 3 pointers which deviates from scoring through the forwards and centers in the paint.

In the NBA, we see players of various positions, including centers, attempting a greater amount of 3 point shots and with some taking ridiculous long distance 3 pointers. Even in the neighbourhoods, we see players attempting to emulate curry in shooting 3s.

However, a thought comes to mind... What are the specific changes that the NBA has seen due to the 3 pointers and how efficient is the 3pointers to the game.

<!-- DATASETS -->
## Datasets
For this analysis, I obtained datasets that was made available on kaggle.com by Nathan Lauga which he in turn obtained from the NBA api available on Python. 

The datasets used are as follow:
1. **Games.csv** (https://www.kaggle.com/nathanlauga/nba-games?select=games.csv)
   - Provides the statistics of the individual team for each game from 2003 to 2021
   - This was used to identify the season to find the mean of the statistics and the win and loss records for the teams across the seasons
  
2. **games_details.csv** (https://www.kaggle.com/nathanlauga/nba-games?select=games_details.csv
   - Provides the statistics for individual players of each game
   - Data is more granular and this was used to find the mean and sum of statistics like FGA and FGM for 2/3pointers
   - Core dataset for this analysis
  
3. **players.csv and teams.csv**\
    (https://www.kaggle.com/nathanlauga/nba-games?select=players.csv) \
    (https://www.kaggle.com/nathanlauga/nba-games?select=teams.csv)
   - Dataset used to identify the names of the players and teams with the relevant ID
   - Important for analysis of team win records across season and identifying the top scorers

4. **NBA api**
   - This was used to generate data for shot charts visualistion
 
<!-- LINES OF ENQUIRY -->
## Lines of Enquiry
To analyse the impact of 3 pointers, we will follow our lines of enquiry to guide us through the analysis.

1. How has the 3 point shot affected the overall points scored?
   * Which statistics will affect points acored?
   * What is the trend like with more 3 point shot taken?

2. How has the number of 3 pts shot attempts and pace of the game changed?
   * What is the proportion of shots like across the seasons?
   * How fast has the game become with more 3 point shots?

3. How has the 3 point Shot affected the Top 10 scorers breakdown in NBA?
   * What are the shots like for these players especially for centers if they make it to the top 10 scorer?
     - _usually centers shots are within the paint but will it change?_

4. How efficient is the 3PT in scoring points and winning?
   * Is the 3 point shot really helping to score more points?
   * By scoring more 3 points, are the teams winning more?

>There are assumptions being made in this to help with the analysis such as equating one FGA to be one possession etc.
 
<!-- CHART EXAMPLES -->
## Chart Examples
Below are some of the charts that you will get to see for this analysis. The charts are created using the matplotlib, seaborn and plotly libraries

![image](https://user-images.githubusercontent.com/50400038/156784814-03e5bf34-0634-40a1-abde-aeea7129b880.png)
![image](https://user-images.githubusercontent.com/50400038/156785702-34b0f26b-cf11-40df-a2f7-f7181b6ee511.png)




