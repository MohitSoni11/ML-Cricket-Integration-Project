# ML-Cricket-Integration-Project
During 11th grade, I did this project with Sundar Uncle to combine my 2 passions -- Machine Learning and Cricket. I used ML to predict different outcomes based on the field, ball length, and player stats.

## Understanding the Data
The Data covers over 1200 cricket matches from 2017 till Pre-COVID (2020).

The Dataset is 3 fold first a CSV file containing each row for a Match, then Batting and Bowling Scorecard CSV files for each match and a CSV file per match containing ball-by-ball commentary for each match.
The data covers International Matches (ODI, T20, Test Match) and leagues namely Indian Premier League (IPL), Big Bash League (BBL) and Pakistan Super League (PSL).

"INTERNATIONAL_MATCH.csv" contains one row per match and contains Superficial data for each match. Data includes:
- Name of the teams
- Unique ID for each team
- Venue, Venue Unique ID
- Date of the Match
- Result of the Match 
- <b>MATCH NUMBER</b> --> This number matches with the scorecards files and commentary files.

The "BATTING" folder contains batting scorecard CSV files. The name of every file in the Batting folder is named as "XXBATTINGSCORECARD.csv" where "XX" is the <b>MATCH NUMBER</b>.
The "BOWLING" folder contains bowling scorecard CSV files. The name of every file in the Bowling folder is named as "XXBOWLINGSCORECARD.csv" where "XX" is the <b>MATCH NUMBER</b>.

"COMMENTARYINTLMATCH" folder contains Ball-by-ball commentary CSV files. The name of every file in the Commentary folder is named as "XX_COMMENTARY.csv" where "XX" is the <b>MATCH NUMBER</b>.

## Let's Understand the Structure by an Example
If a row in the "INTERNATIONALMATCH.csv" file contains MATCH NUMBER "12345", then its Batting Scorecard CSV file will be in the "BATTING" folder named "12345BATTINGSCORECARD.csv", the Bowling Scorecard CSV file will be in the "BOWLING" folder named "12345BOWLINGSCORECARD.csv", and the Commentary CSV file will be in the "COMMENTARYINTLMATCH" folder named "12345COMMENTARY.csv".