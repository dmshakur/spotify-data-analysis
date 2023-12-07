
# Spotify data analysis project

Data source: https://www.kaggle.com/datasets/dhruvildave/spotify-charts
Start date: Dec. 6th 2023
End date: ...

### Purpose and goal of the project
Soley to practice skills learned in SQL, Python and data visualization.

I had asked ChatGPT 4 to make me a project prompt, but after some thinking I realized that I didn't
want to do what it had originally had me do and analyze product sales data, as that is not very intrinsically interesting to me.
I then thought that a great thing for me to do would be to analyze Spotify data, as someone that already loves and adores Spotify
this makes perfect sense! So I had ChatGPT rewrite the prompt to accomodate for this change.

## Part 1: Basic data checks and moving data into a sqlite3 database
Starting with './data/raw_spotify_charts_data.csv'.
Check the data for null values, convert some columns to data types, and then put the csv turned dataframe into a sqlite3 database file.

After moving the dataframe into a sqlite3 database soley for the ability to practice using sql, and then doing basic checks to ensure that the database trasferred over fine.

#### Data preprocessing and cleaning
Data preprocessing and cleaning for this dataset was very minimal, where only one column had problematic values.

## Part 2: Basic data exploration
My goal here is to better understand the data in terms of popularity, like what genres are more prevelant or what artists have the most listens etc.