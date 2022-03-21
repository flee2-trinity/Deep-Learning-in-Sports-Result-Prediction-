# Deep-Learning-in-Sports-Result-Prediction-
Several self-designed neural network models for NBA game result prediction, including single game, play-by-play and ranking.
<br />
I use Google Colab during the whole project, and then I uploaded about half of my code here on 3/21/2022.
<br />
I would recommend anyone who actually wants to run the code to visit my google drive folder which includes all my code, NBA data, my data, and plots. Also, using Google Colab GPU is free and convenient! 
Here is the link. https://drive.google.com/drive/folders/1LytgjgUHSfSxr0cgXDPOORyllg0aCujr?usp=sharing
I'm still working on the thesis, so it is not so organized yet. I will finish this project by May 2022 with a thesis to explain it.
<br />
## Single Game Prediction
I have built many types of models for single game prediction.
<br />
NN models including teams' names in one hot coding, but no team stats
<br />
NN models including teams' names in one hot coding with team stats
<br />
NN models including all stats of a single game and winning rating of a team
<br />
RNN model including all stats of a single game and previous records of a team
<br />
LSTM model including all stats of a single game and previous records of a team
<br />
## Play By Play Prediction
<br />
## Ranking Prediction
Basically I have ranking prediction which uses 25% of previous season games data to predict the new season ranking. I also have a power ranking prediction when testing the models. My models actually preforms alot better than elo method espacially in first half of the season.
