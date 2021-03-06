# Group6-FinalProject
# NBA Crystal Ball 
## Predicting NBA Statistics for the 2020-21 Season
For our final project we used NBA data from https://www.basketball-reference.com/ to predict which teams will make the playoffs, which team will win the championship, as well as who will win the Most Valuable Player (MVP) and Rookie of the Year (ROY) awards. To make our predictions we leveraged SK learn and regressions to predict future outcomes based on historical data. The most challenging aspect of our project was collecting all of the data. We needed a large amount of data to leverage SK learn so we needed to manually export several CSV files from Basketball Reference both for individual player statistics and team statistics. 

When predicting which teams would make the playoffs, we looked at adjusted margin of victory, adjusted offensive rating, adjusted defenseive rating, and adjusted net rating. Being an adjusted rating simply means that the level of competition was taken into consideration. We trained out data model using these stats and 10 years of previous NBA team data to determine how those four statistics impacted total wins. We then took the current year to date performance of teams and predicted how many wins they would end up with based on those statistics. 

For predicting MVP and ROY, we took the same approach we did for predicting playoff teams, but leveraging individual player statistics. We took historical player data for several years and trained our historical data on a set of individual statistics to see how impactful those were on winning either award. We then used SK learn to predict which players were having MVP or ROY seasons (a binary 1 or 0. 1 meaning 'yes' they would qualify as an MVP or ROY season and 0 meaning 'no' their season does not qualify), as well as their percent chance to win the award based on their year-to-date season performance. 

Check out our github pages and Tableau Public Story for our graphics and more analysis. 

https://wgaechter.github.io/Group6-FinalProject/index.html

https://public.tableau.com/profile/jennifer.powell8088#!/vizhome/JenniferProject3/PredictingNBAStatisticsforthe2020-21Season?publish=yes


