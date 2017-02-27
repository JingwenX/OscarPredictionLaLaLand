# OscarPredictionLaLaLand
Using a regression model to predict how many Oscar awards would La La Land (2016) win this year.

--prediction before announcement--
fit1 <- glm(df_noone$Awards ~df_noone$Nominations, family = gaussian, data = df_noone)
awards_with_14_nomination  = 0.52549+14*0.398 = 6.09
After my first analysis with linear regression, the predicted awards for La La Land (2016) 
who has 14 nominations, is predicted to have around 6 awards:)

--News of Announcement Feb 27th, 2017--
La La Land did get 6 awards!!!
https://www.nytimes.com/2017/02/26/movies/oscars-academy-awards.html
