# Investigating-Fantasy-Football-Success-For-Wide-Receivers

Title: Evaluating Wide Receiver Performance in Fantasy Football

Abstract: 
Fantasy football is a multi-billion dollar industry and has become a staple for casual and die-hard football fans. The use of data analysis has also had a lot of growth in the fantasy football community, mainly to make projections on how many points players will score so that fantasy players can gain any possible edge. Oftentimes, there are factors that cause players to exceed or fall short of their fantasy projections. The goal of this project is to look at wide receiver data to make predictions on players who could be huge values and/or busts next season based on underlying metrics. 

Context:
The stakes of Fantasy Football can be very high. Whether it is professional players playing for huge prizes or just your common player playing for bragging rights over their friends, players are heavily invested and want to win, badly. An inevitable part of Fantasy Football is that there will be players who fall very short of their expectations. On the flipside, there are players who exceed their expectations. Oftentimes, there are very obvious reasons for why one or the other happens such as injuries or a change at quarterback leading to more or less success. Other times, however, there can be more underlying issues that may have suggested success (or lack thereof).

The ultimate goal of Fantasy Football is to win, and have fun while doing it. There is undeniably a solid amount of “luck” involved in Fantasy Football. However, with so much data and player evaluation metrics now at our disposal, Fantasy players rely heavily on player projections to help them craft their rosters. Player projections are extremely challenging and no one can get them right all the time. But, it is important for the Fantasy Football community to have people who are dedicated to doing their best at making accurate projections for players. 

Proposal:
I hope to investigate wide receiver data specifically. The reasoning is because they are often the most variable performers in the Fantasy Football world. They are also some of the most influential players, and selecting the right/wrong receivers in your dravt can make or break the chances of winning your league. The main question that I am trying to answer is: What statistics are the biggest correlations of success for wide receivers in Fantasy Football? Based on these correlations, who are some wide receivers that players should target or stay away from in drafts for next season?

I plan on using wide receiver data from past seasons to find correlations to fantasy performance in terms of points scored. From there, I hope to take the results from the correlation tests to identify players who performed well/poorly in these metrics and compare them with the amount of fantasy points these players scored last season. I also plan on running regression models to attempt to answer some of the same questions. My analysis will be done predominantly in R. 

I expect to find that there were a fair share of wide receivers who either outperformed their ability or vice versa. These players would then presumably be due for negative or positive regression to the mean for the upcoming season. My initial prediction is that wide receiver targets/target share percentage is going to be the biggest indicator of fantasy points scored. I also hope to be able to use what I find for my own Fantasy Football drafts in the upcoming season. 

Conclusion:
Player projections are challenging, and over and under performance is often an issue for Fantasy players when trying to win a championship in their respective leagues. Success in one season does not guarantee success in another, and a bad season one year can just as easily turn into a good one for the next season. It is important for Fantasy Football players to have access to projections that are backed up by what the data says. I plan to use data in order to assess wide receiver performance and find receivers that Fantasy players should either target or steer clear from in the 2022 season. 

This project has the potential to be expanded in the future. I could look at all the other positions in the Fantasy Football player pool as well (Quarterbacks, Running Backs, Tight Ends). I hope to use this project for my own Fantasy drafts this season, and possibly expand in future years. 


Data Usage:
The data that I am using for my project can be found on Fantasydata.com. It is a outstanding website for sports nerds such as myself. They have access to pretty much all data from major sports leagues. The NFL data is extremely nice, as the stats range from standard, box score statistics to advanced statistics that are not as common for the average football fan. 

I have three data sets that I am planning on using for the project. The first is a set of standard wide receiver fantasy statistics like receptions, yards, touchdowns, targets, etc. The second set contains advanced statistics such as air yards, air yards per game, target share, and redzone targets. Lastly, the third data contains efficiency statistics. This includes target separation, contested catch rate, yards per target, and drops (this is the data set that will be used the least.)



