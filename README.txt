This repository contains the tools to analyze chess games contained in a pgn format. 
If you want to use the sample games already contained within this repository, you do not need to run ETL.ipynb
The data contained is sourced from https://www.kaggle.com/datasets/bavlymoheb/lichess-sample-pgn
If you want to analyze your own pgn file, run it through the ETL.ipynb file to construct a csv file containing a subset of 50000 games which you can use to analyze.

EDA.ipynb offers a quick exploratory data analysis using command line tools.

Run R_Visuals.Rmd to get a more in-depth analysis of games. The pre-existing HTML file shows the analysis done on the current dataset.