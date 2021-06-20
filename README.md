# Sports Gambling

## Summary

Often referred to as “games of chance”, gambling can often be broken down into relatively basic mathematics. All outcomes in gambling games have defined probabilities that depend on sample spaces, or the total number of possible outcomes. In poker, the odds of having a winning hand can be calculated based on the probabilities of the cards drawn, as well as some underlying psychology.
Horse racing and other sports events can also be broken down in a similar way. By analyzing physical attributes of each of the horses such as average speed, number historical wins, terrain conditions, weather, and dozens of other data points, we can create a model that can return probabilities of certain horses winning. 
Hong Kong has the largest industry for betting on horses with an average pool size of $12.7 million per race, followed by France with an average pool size of $2 million. 


## Problem Statement

Probability is at the center of all gambling. For simple card games such as blackjack or poker, the probability of winning can be easily understood based on which cards a user has in their possession as well as their opponents’ cards or the cards in the flop. Skilled players recognize the sample space of the game and the probabilities associated with each of their hands. They are able to make calculated bets based on the likelihood of winning. If their odds of winning are low, they may bet very little or fold.

It’s not enough to know the probabilities of winning a hand are. We are interested in how much money we can make from each game. This is called the expected value and is calculated based on the probabilities multiplied by their associated gain or loss. For example, casinos have a negative expected value due to the house advantage in all games. 

More often than not, gamblers overleverage their bets due to superstitions, logical fallacies, and a general lack of understanding for the underlying mathematics of gambling, making betting against them much more lucrative. If the calculated risk from our expected value is much less than the implied risk of the actual value of the bet, it may be financially beneficial to take advantage of that arbitrage. For example, if we calculate the odds of a horse winning placing first in a race is 60% likely, and the betting odds for that horse are +100 (or 2/1  or 50%), we create a situation which we are able to double our money on a 60% chance. By utilizing the Kelly Criterion, we can wager an appropriate level of money for each bet, ensuring that we don’t overextend our positions

We have access to several years of historical racing data from two famous tracks in Hong Kong containing the date, track conditions, track surface type, and dozens of other useful attributes. We can generate profiles for each horse that participated and build a statistical model to help us evaluate the likelihood of each horse placing in the race. 

## Data Used

- [Horse Racing in HK](https://www.kaggle.com/gdaley/hkracing):
Horse racing data containing horse data as well as race statistics spanning from 1997 to 2005. 


- [Horse Racing Dataset for Experts](https://www.kaggle.com/hrosebaby/horse-racing-dataset-for-experts-hong-kong):
A collection of five datasets containing barrier trails data, horse info, race results, trackwork, and a collection of comments about each horse. The data spans from 2015 to 2017

-[Hong Kong Horse Racing Results 2014-17 Seasons](https://www.kaggle.com/lantanacamara/hong-kong-horse-racing?select=race-result-race.csv):
Data from 2014 to 2017 containing horse data as well as race statistics. 



The following topics will be covered in this project:
* Importing the Data
  * Iterating over multiple files to combine our data
* Exploratory Data Analysis
  * Plotting the data to discover sequences, trends, and correlations 
* Data Wrangling
  * Data Restructuring
  * Attribute Creation
  * NaN Imputation/Removal
* Model Development
  * Neural Networks

