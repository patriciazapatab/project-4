# Project 4: Gaming Industry analysis


# Introduction
GameStore Perez INC. is a family-owned company founded by Marco Perez in 1973. Over the past 50 years, Marcos Perez and his family have brought joy to the entire neighborhood through their board game store. With the entry of the third generation into the business, the family is contemplating diversifying by entering the world of video games. This project aims to analyze the current board game landscape and explore the potential offering of video games, providing clarity on the possible next steps for GameStore Perez INC.

<br>

# Data Source
<br>

The data used for the project includes the following datasets from Kaggle. 

- [Board games](https://www.kaggle.com/datasets/sujaykapadnis/board-games?rvi=1)
(updated 1 month ago)

- [Video games releases](https://www.kaggle.com/datasets/ghassenkhaled/video-games-data?rvi=1)
(updated 2 months ago)

Both datasets contain data from 1980s up to 2016 so that is the time range used for the project. 

<br>

# Workflow & methodology

The main tools used for this project have been: 

- **Python**:
    - Pandas library for dataset cleaning and transformation.
    - Pymysql, SQLAlchemy, os, dotenv, and getpass libraries for establishing the connection with the SQL database and working with SQL from Python.

- **SQL**: Language used to query board games and video games databases to answer client requests and gain knowledge about consumer preferences.

- **Tableau**: Used for visualization and extraction of conclusions from the video games releases analysis.

<br>

<br>

# SQL Queries

In the SQLqueries.ipynb file located in the notebooks folder, Luis, Marco's son, utilizes the public board games database to comprehend client preferences and assist a client in discovering the ideal board game.

Towards the end, he begins pondering questions such as which video games are the best-selling. Following several queries, he opts to delve into visualizing the data to draw additional conclusions.


# Tableau analysis and results

To better communicate the results of his findings to the rest of the family, Luis creates a Tableau story containing several dashboards featuring compelling insights into future video game releases. It is possible to explore the Tableau story [here](https://public.tableau.com/app/profile/patricia.zapata.blanco/viz/VideoGamesanalysis_17005247117480/VideoGamesIndustry?publish=yes).


# Conclusions

After the analysis of the current board games situation and the preliminary analysis of video games releases history GameStore Perez team gets to the following conclusions: 

- Board games prove to be a reliable choice. There is a wide variety of categories and features, ensuring an ideal board game for every individual and occasion.

- Additionally, the data illustrates the board game market's consistent growth. GameStore INC. decides that despite considering the possibility of entering the video game industry, it will continue to prioritize its board game store at all times.

- Regarding the world of video games, it is evident that console releases are the primary factor influencing game launches and their types. For this reason, the company sets as next steps analyzing the trend in console releases and their potential impact on the market. 

- On the other hand, there is a geographic component to consider. If they ultimately decide to venture into the world of video games, it will be with a keen awareness of the local market they are targeting.