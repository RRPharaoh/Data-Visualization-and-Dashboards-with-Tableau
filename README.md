# Project-Tableau

## Project/Goals
My goal with this project is to find a correlation between player stats, wages and the teams that they play for utilizing the FIFA 18 game data.

## Process
### Analysis
I started by analyzing plyer data on a geographic basis, determining where some of the best players in the world came from. I then look at key metrics such as age, overall stats, teams they played for as well as wages. I then sorted teams by location, value, and wages. I tried to find a correlation between wages and players statistics.  

### Visualization
Once I was able to stablish a baseline, and figure out some connections and correlations, I put together some key visualizations within tableau that would highlight some of the insights that I was able to determine.

Here is a link to the tableau presentation: https://public.tableau.com/views/Visualization_project_finale/Presentation?:language=en-US&publish=yes&:display_count=n&:origin=viz_share_link

I will also provide a PDF version within the project folder.
## Results
The option I chose was the FIFA 18 Game dataset. My initial exploration started with the nationality of each player in the dataset. The first data set I made was heat map for each nation in the data set group by the sum of players from nation. I also made a geographic map (world) map to highlight all the different nations represented in the dataset. I initially had one geographic heat map, but I decided to separate them into two to better visualize the diversity of the players. 

Next, I looked at the 'overall' stat distribution sorted by Nationality, limited to the top 20 nations by representation (sum of players from each nation). I decided to utilize a scatterplot as I felt it best visualized quantity, range, as well as overall skill.

I wanted to analyze the average overall of the entire dataset sorted by age, so I created a bar graph. During my analysis, I noticed that most players peak at about the age of 30, however even after 30 there is a consistent spread across each age group unto about age 40, however the quantity of players significantly decreases after age 32. So, I took all player at the age of 32 and created a table. There happened to be an outlier in that age group, Cristiano Ronaldo. I looked at the value of that player’s team; Real Madrid and decided to explore further.

Something that was consistent across the board was value, wages and the overall stat of players. Teams that had a higher overall value would usually pay higher wages and employ the best players, initially I thought there would be outliers, but instead I found consistency, across the top 5, with decreases in both overall stat and wage the lower the value of the team. This was also true across other minor stats such as:
- GK reflexes
- Sprint Speed
- finishing

The top 5 teams were usually interchangeable, other top 20 teams shuffling around. 

A hypothesis can be made that the best teams (top 5) in FIFA 18, will typically have the highest value, pay the highest wages, and have players with the highest stats in two or more categories. 

## Challenges 
Most challenges I encountered revolved around Tableau and my familiarity with it, as it was my first time utilising it. In terms of the dataset, while the data is comprehensive regarding gameplay mechanics, it is very limited in scope when we look at other relative stats involving the sport of football. In order to further analyze the area that I focused on (club value & wages) I would need examine more comprehensive data, that was composed of real-world transactions. 

## Future Goals
I would like to examine real world data, to get a better understanding of what determines the value of a football club, as well as a market indicators and trends that affect and a player/'s value.
