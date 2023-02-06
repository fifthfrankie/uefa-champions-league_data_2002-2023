# uefa-champions-league_data_2002-2023
Champions League data from 2002-2023 (2023 up-to-date until 06/02/2023)  

**Note**: 2014-2015 is the first season that includes **'Time'** & **'Attendance'** data, this is not included in any seasons prior.  
**Note**: 2016-2017 is the first season the **'xG'** columns are available and also the **'Extra Time Required'** column, this is not included in any seasons prior.  

**Raw data included (from FBRef.com)**  

**'Round'** - Competition stage (eg. First round, Semi-Final etc.)  
**'Wk'** - Gameweek of competition  
**'Day'** - Day of the week game played  
**'Date'** - Full date of game played  
**'Time'** - Time of KO **(only included from 2016-2017 season onwards)**  
**'Home'** - Home team name (raw data includes flag call (eg. "eng" after name for England flag on website))  
**'xG'** - Expected Goals (xG) is a metric designed to measure the probability of a shot resulting in a goal  
**'Score'** - Final score  
**'Away'** - Away team name (raw data includes flag call (eg. "eng" after name for England flag on website))  
**'Attendance'** - Registered attendence for match  
**'Venue'** - Venue name of event   
**'Referee'** - Referee full name for match  
**'Notes'** - Additional information such as Leg number, who won that leg, if ET was required   

**Additional data (clean, useful for analysis)**   

**'Home_Clean'** - Home team name  
**'Away_Clean'** - Away team name  
**'Home_Score'** - Home goals   
**'Away_Score'** - Away goals  
**'Leg 1'** - True or False (1,0)   
**'Leg 2'** - True or False (1,0)   
**'Extra Time Required'** - True or False (1,0)   
**'Home_Score_2'** - Home goals **Only required if penalties occur and 'Home_Score' is no longer a whole number value**  
**'Away_Score_2'** - Away goals **Only required if penalties occur and 'Away_Score' is no longer a whole number value**  
**'Home_Pens'** - Home team penalty goals (only in the event of a penalty shootout)  
**'Away_Pens'** - Away team penalty goals (only in the event of a penalty shootout)  
