# IMDb 2020 Dataset Analysis
This repository contains an analysis of IMDb data focusing on the top-rated movie of 2020, the most popular actor of 2020, statistical analysis using ANOVA (Analysis of Variance), and trend analysis to uncover patterns and shifts in movie ratings and actor popularity.

# Dataset Overview
The dataset used in this project contains information about movies, actors, ratings, and votes from IMDb. The primary focus is on data from the year 2020, including:

- Top-rated movie of 2020: Based on weighted average ratings.
- Most popular actor of 2020: Based on the number of appearances and overall popularity during the year.
- Statistical analysis: Using ANOVA to compare different groups within the data (e.g., genres, directors) and assess the significance of differences in ratings and votes.
- Trend analysis: Examining shifts in ratings, popularity, and other metrics over time to identify emerging patterns and changes throughout the year.
  
# How to Replicate This Analysis
To replicate the analysis, you will need to download the necessary [public IMDb datasets](https://developer.imdb.com/non-commercial-datasets/), [top 1000 IMDb Dataset](https://www.kaggle.com/datasets/inductiveanks/top-1000-imdb-movies-dataset) and place them in the appropriate folder structure. Follow the steps below:

Step 1: Download IMDb Datasets
You can download the following datasets from the IMDb public dataset page:

- name.basics.tsv.gz - Contains information about actors, directors, and other key personnel.
- title.ratings.tsv.gz - Includes movie ratings and the number of votes.
- title.basics.tsv.gz - Contains details about movies, including titles, genres, and release years.
- title.principals.tsv.gz - Information about the primary actors, directors, and writers associated with each title.
  
Step 2: Place Datasets in the Correct Folder Structure
After downloading the files, create a folder named |data/tsv.gz_files/ in the repository root and place the .tsv.gz files inside it. The folder structure should look like this:
```
├── data/
│   └── tsv.gz_files/
│       ├── name.basics.tsv.gz
│       ├── title.ratings.tsv.gz
│       ├── title.basics.tsv.gz
│       └── title.principals.tsv.gz
|   └── imdb_top_1000.csv
```
