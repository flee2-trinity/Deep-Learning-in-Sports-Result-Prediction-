# Deep-Learning-in-Sports-Result-Prediction-
Several self-designed neural network models for NBA game result prediction, including single game, play-by-play and ranking.
<br />
I use Google Colab during the whole project, and then I uploaded 30% of my code here on 3/21/2022.

<br />
I have tried different learning rate, loss functions, layer size, regression methods, seasons for each of them. 
<br />
Here is the thesis link:
<br />
https://digitalcommons.trinity.edu/compsci_honors/65/
<br />
I would recommend anyone who actually wants to run the code to visit my google drive folder which includes all my code, NBA data, my data, and plots. Also, using Google Colab GPU is free and convenient! 
<br />
Here is the link: https://drive.google.com/drive/folders/1LytgjgUHSfSxr0cgXDPOORyllg0aCujr?usp=sharing

<br />

## Single Game Prediction
Built many types of models for single game result prediction:
<br />
NN models including teams' names in one hot coding only
<br />
NN models including teams' names in one hot coding with team stats
<br />
NN models including teams' names in one hot coding with team stats and averaging stats of n previous games
<br />
NN models including all stats of a single game and winning rating of a team of n previous games
<br />
RNN models including all stats of a single game and previous records of a team
<br />
LSTM models including all stats of a single game and previous records of a team
<br />

## Play-by-Play Prediction

Using play-by-play data to predict the winner during a game
<br />
## Rankings Prediction

Basically I built rankings prediction based on my best single game prediction models which uses 25% of previous season games data to predict the new season ranking. I also have a power ranking prediction when testing the models. My models actually preforms a lot better than elo method espacially in first half of the season.
<br />

## Data Source
National Statistical: NBA Season 12-19: Team Stats, Play-by-play Stats
<br />
531: Elo Rating
<br />
