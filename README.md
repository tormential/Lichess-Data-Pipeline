# Lichess-Data-Pipeline
A data pipeline analyzing move quality in chess, relative to elo rating, time expenditure, and time control of the games.

This repository contains the tools to analyze chess games contained in a PGN format. 
If you want to use the sample games already contained within this repository, you do not need to run ETL.ipynb; the games used for analyzing are stored within lichess_stockfish_sample.csv
The data is sourced from https://www.kaggle.com/datasets/bavlymoheb/lichess-sample-pgn, which in turn is sourced from https://database.lichess.org/#standard_games

If you want to analyze your own pgn file, run it through the ETL.ipynb file to construct a CSV file containing a subset of 50000 games which you can use to analyze. Also feel free to change the quantity of games you wish to analyze, the number chosen above was arbitrary.

EDA.ipynb offers a quick exploratory data analysis using command line tools, to help gain a better understanding of the data.

Run R_Visuals.Rmd to get a more in-depth analysis of the games. The pre-existing HTML file shows the analysis done on the current dataset.
