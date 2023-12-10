# Spotify Data Analysis Project

## Introduction
**Project Duration**: December 6th to December 12th, 2023

### Participant Information
- **Name**: D'Angelo Shakur
- **Current Location**: Medellín, Colombia
- **Country of Origin**: United States
- **Contact**: 
  - Email: dangeloshakur@gmail.com
  - Phone: +57 321 450 7954 (Colombia)

### Files and file structure
- .git/
- data/
    - raw_spotify_charts_data.csv
    - raw_soptify_charts_data.db
- figures/
    - 5 different png files created from seaborn from the data visualizations created in data-analysis.ipynb
- notebooks/
    - data_analysis.ipynb
    - data_processing.ipynb
- README.md
- README.md.old
- chatgpt_project_prompt.md

## Data Source and Characteristics
- **Source**: [Spotify Charts Data on Kaggle](https://www.kaggle.com/datasets/dhruvildave/spotify-charts)
- **Size**: Exceeding 3 GB (not hosted on GitHub)
- **Structure**: 
  - Rows: 26,173,514
  - Columns: 9 (title, rank, date, artist, url, region, chart, trend, streams)

## Project Objectives
This project is a hands-on exercise to enhance my skills in SQL, Python, and data visualization. Initially inspired by a ChatGPT-generated prompt, I pivoted towards analyzing Spotify data, aligning with my personal interest in the platform. The project is a blend of self-driven learning and guided assistance from ChatGPT, facilitating a deeper understanding of data analysis methodologies.

### Role of ChatGPT
ChatGPT played a pivotal role, not just in answering specific queries but also in broadening my understanding of data analysis techniques and concepts.

## Methodology
### Data Preprocessing and Import
- Initial steps included checking for null values and data type conversion.
- Data was transferred into a SQLite3 database, enabling SQL practice and ensuring data integrity.

### Data Exploration and Visualization
The primary aim was to discern trends in music popularity, genres, and artist performances. The analysis revolved around five key queries:
1. Streams per country
2. Number of songs per country
3. Artist comparison in streams vs. song count
4. Cumulative trends in streams
5. Cumulative trends in songs

### Dataset Limitations
The dataset comprises top-charting songs on Spotify, representing a subset of the platform's total music library. This limitation should be considered when interpreting the results. There also was no genre data in the dataset, which is an important metric when categorizing music data.

### Analytical Challenges
While the questions posed may not encompass the entire scope of potential data analysis, they serve as effective exercises in data handling and interpretation.

## Insights and Learning
- Regional Usage: The data revealed lower Spotify usage in regions like Africa and the Middle East, contrasting with higher usage in Western Europe and North America. A notable rise in both listeners and creators was observed in Latin America.
- Technical Insights: 
  - **Pandas**: Utilized extensively with minimal challenges.
  - **Seaborn**: Focused on achieving desired visualizations, refining my approach to data representation.
  - **Jupyter Notebooks**: Provided a straightforward and efficient environment for the project.
  - **SQLite3**: Enhanced my SQL skills, particularly in complex query formulation.

## Acknowledgments
Special thanks to my mentor, Logapriya Viswanathan, for her invaluable guidance and support throughout this project.

---

*This README has been revised for clarity, structure, and presentation, ensuring a concise and informative overview of the Spotify Data Analysis Project.*
