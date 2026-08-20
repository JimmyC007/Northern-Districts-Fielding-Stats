# Project Outline
In the game of cricket there are three basic positions, batters, bowlers, and fielders. Batting and bowling staistics have been recorded in depth for decades, fielding statistics however have not been captured to the same detail. Successful catches and runouts are recorded against a fielder's name but missed chances, close calls, and spectacular run-saving dives aren't captured nearly as consistently. I worked with a coach from Northern Districts Cricket Assosciation to build a system that would capture the fielding performance of the team and generate reports the coaches could then use to identify player strengths/weaknesses. The team played in two competitions, the Hallyburton Johnstone Shield (50 over format) and the Super Smash (T20 format). 

The main new concept was the idea of assigning every wicket-taking chance a grade from 1-3 which could easily be converted to an easy/medium/hard difficulty scale. Players were expected to successfully take every grade 1 chance while successful grade 3 chances came through an extra effort from the fielder.
<br /> 
## Part 1 Create App
I needed to create a tool the coaches could use to record what was happening during each game. The tool needed to be simple due to the fast nature of T20 cricket while also capturing enough detail to conduct meaningful analysis. I settled on using Google Forms with an Appsheet front end for the coaches to use.

## Part 2 Generate Game Report
After each game the coach wanted the collected data to be recorded through visuals and notes which could then be shared with the players. I set up an R script that cleaned the data and produced a report in markdown that I could then send to the coaches within minutes of a game finishing.

## Part 3 Visualize 
The coach wanted a dashboard that could be used to keep track of all the player's fielding stats throughout the season and a separate dashboard to summarize the season performance. I used Tableau to produe these interactive dashboards and share them with the coach. [This dashboard](https://public.tableau.com/views/ND2223CoachesGraphs/CoachingGraphs?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link) is an example of the summary the coaches had available to track individual performances throughout the season.

