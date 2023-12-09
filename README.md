
# Spotify data analysis project

Data source: https://www.kaggle.com/datasets/dhruvildave/spotify-charts

Start date: Dec. 6th 2023

End date: Dec. 12th 2023

### Dataset
Over 3 GB in size, it is not included in my github profile

**Dataset shape**: Columns 9, Rows 26,173,514

**Columns**: title, rank, date, artist, url, region, chart, trend, streams

### Purpose and goal of the project
Soley to practice skills learned in SQL, Python and data visualization.

I had asked ChatGPT 4 to make me a project prompt, but after some thinking I realized that I didn't
want to do what it had originally had me do and analyze product sales data, as that is not very intrinsically interesting to me.
I then thought that a great thing for me to do would be to analyze Spotify data, as someone that already loves and adores Spotify
this makes perfect sense! So I had ChatGPT rewrite the prompt to accomodate for this change.

## Basic data checks and moving data into a sqlite3 database
Starting with './data/raw_spotify_charts_data.csv'.
Check the data for null values, convert some columns to data types, and then put the csv turned dataframe into a sqlite3 database file.

After moving the dataframe into a sqlite3 database soley for the ability to practice using sql, and then doing basic checks to ensure that the database trasferred over fine.

#### Data preprocessing and cleaning
Data preprocessing and cleaning for this dataset was very minimal, where only one column had problematic values.

## Data visualization and exploration
My goal here is to better understand the data in terms of popularity, like what genres are more prevelant or what artists have the most listens etc.

There were 5 different questions I posed on the data.
1. How many streams were there per country?
2. How many songs were there per country?
3. How do artists compare their number of streams to the number of songs that they have?
4. What are the cumulative trends in streams?
5. What are the cumulative trends in songs?

#### The data
The dataset that I worked with contained only songs that were in the top charts of spotify, so the results are not totally complete and an accurate representation of anything but of what makes a hit song.

#### My approach was not perfect
The questions I asked of the data here may not be the 'best' questions to ask, nor may have I asked them in the best way, meaning that I did not take the data into my notebook and provide an answer the best way through my code and data transformation. But this is merely a repitition in my exercization of my data analytics skills, and I do want to complete it and not spend too much time working with this data.

#### What I learned
It is really hard to tell what I actually learned here, as there are questions you can ask and wonder that make the data seem very incomplete. For example, this data is only 4 years of the entirety of the operations of Spotify as a company. One insight that I learned of was that Spotify is used less in areas like Africa, and the middle east, and is obviously more prevalent in places like western Europe and North America. There is however a large increase in listeners and creators in Latin America.

Overall insights were not very valuable or insightful, but that's okay, that is not exactly what this project is for.

## What I learned, technically with using Python and SQL
The tools I primarly used are as follows:
* Pandas
* Seaborn
* SQLite3

Special thank you to my mentor `Logapriya Viswathana`
