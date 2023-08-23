# Nba-Price-Prediction

This project aims to use Machine Learning methods to predict NBA players' 
Mojo price changes for the upcoming 2023-2024 NBA season. 

Disclaimer: I do not endorse irresponsible gambling and this project is not
to be taken as betting advice. I personally have not invested any money into 
sports betting and am not affiliated with Mojo in any way. This is just for fun.

Mojo is a sports betting website which aims to predict a basketball player's statistics at the end of their career. It is conceptually analogous to stocks, 
except the underlying value that consumers bet on is based on a formula involving players' projected career statistics. 

The mojo value formula for NBA career stocks is as follows:
0.0125 steals + 0.0125 blocks + 0.01 points + 0.0075 assists + 0.005 rebounds + 0.005 3pts made + 0.0025 plus minus - 0.0125 turnovers - 0.01 fg missed - 0.005 ft missed

In this project, we train a machine learning model to predict how players'
careers will turn out based on past players' careers. To do so involves 4 steps:
1. Data Collection using web scraping
2. Data Preprocessing to filter for relevant data
3. Model training
4. Model evaluation