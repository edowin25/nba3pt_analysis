## An analysis how the 3 point shot impact the NBA game of basketball

### Brief Introduction
This project analyses how the 3 point shot changes game from season to season. We will look at the following in this project. You can use the table of contents to access the necessary sections for your information

<!-- TABLE OF CONTENTS -->
<details>
  <summary><b>Table of Contents</b></summary>
  <ol>
    <li><a href="#project-context">Project Context</a></li>
    <li><a href="#datasets">Datasets</a></li>
    <li><a href="#lines-of-enquiry">Lines of Enquiry</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- PROJECT CONTEXT -->
### Project Context
Over the years, we have seen the popularity of the 3 point shot in the game of basketball rise all around us. This whole hype first started out with Stephen Curry, dubbed as the greatest shooter of all times and the Golden State Warriors revolutionalise a new type of offense where it focuses on small ball and 3 pointers which deviates from scoring through the forwards and centers in the paint.

In the NBA, we see players of various positions, including centers, attempting a greater amount of 3 point shots and with some taking ridiculous long distance 3 pointers. Even in the neighbourhoods, we see players attempting to emulate curry in shooting 3s.

However, a thought comes to mind... What are the specific changes that the NBA has seen due to the 3 pointers and how efficient is the 3pointers to the game.


<!-- DATASETS -->
### Datasets
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
### Lines of Enquiry
To analyse the impact of 3pointers for our analysis


