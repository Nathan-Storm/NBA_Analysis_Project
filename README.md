# Description
This project explores correlations in stats from the 2010 season and tests three-point stats against scoring to see how things have changed over the decade. We use 2022 as the decade's endpoint, since the 2 earlier seasons were cut short by the virus.

# Analysis
Through analysing the correlations, I concluded the largest growth was in three-point volume. I took three-point attempts and makes and compared them with points. I used an AI integration response prompt to determine what other stats could improve these correlations. I used true shooting percentage and assist percentage, as well as three-point percentage, within a linear regression model to predict a player's next season's points per game. 

# Results
On the test set for the 2022 season, the baseline mean error of average points was about 5. Incorporating FG3A, FG3M, TS_PCT, AST_PCT, and finally FG3_PCT into a linear regression model improved the prediction analysis to only being off by about 3.97. 

# Limitations
Correlations show relationships, not concrete facts that one stat may cause another. The results from my model, while accurate for the 2022 season, are not guaranteed to be as accurate for other seasons. The same goes for trying to predict the next decade; I understand that this is not a flawless prediction model. 
