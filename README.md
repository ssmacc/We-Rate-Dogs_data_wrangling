# WeRateDogs Twitter Data Wrangling

Wrangling process takes data from three sources. These being a twitter archive in CSV format, a TSV file containing neural network data on tweet images and finally JSON data aquired using the Twitter API to be used for analysing likes and retweets. 

Numerous quality and tidyness issues were noted and cleaned through the wrangling process. Relevant data from the three sources was then compiled and saved into a master CSV dataset for analysis.

As this project only focused on the wrangling process, analysis is very brief and contains only initial findings. 

## Info

- *files* - Folder containing tsv and csv data files.
- *act_report.pdf* - Brief PDF overview of some initial findings.
- *tweets_data_json.txt* - tweet data dump
- *twitter_dataset_master.csv* - Cleaned and compiled dataset ready for analysis. 
- *wrangle_act.ipynb* - Primary notebook containing the wrangling process.
- *wrangle_report.pdf* - Brief PDF overview of wrangling process. 

## Requirements/libraries

- Python 3
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Os
- Requests
- Tweepy
- Json
- Time
- Warnings