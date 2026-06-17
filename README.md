## Hotstar_Data_Analysis (Interactive Dashboard Creation Using Power BI)
I have developed comprehensive Disney+ Hotstar dashboard in powerbi to analyze data. This process involved several stages, data cleaning, shaping data before turning into interactive dashboard.

### Project Objective 
Analysis on disney_plus_shows which has been added in 2019-20 released from 1929 to 2020 with all genre e.g. Comedy, Drama, Romance and Animation etc. based on sample data taken from Kaggle.
### Database Used
- <a href="https://github.com/vikashsinghba/Disney_Hotstar_Data_Analysis-/blob/main/disney_plus_shows.csv">Data Set-disney_plus_shows</a>

### Dashboard Parameters
- KPI cards: Genres | Directors | Actors
- Donut chart: content split by type
- Tree-map: average IMDB rating by genre
- Filled World map: total IMDB votes by country
- Area chart: content added 1920–2020
### Dashboard Interaction


### Dashboard

<img width="679" height="376" alt="Screenshot Hotstar Power BI Dashboard" src="https://github.com/user-attachments/assets/aed61c0e-0b7b-47bd-a021-e38f9293b550" />


### Process
Started with a raw dataset (992 rows, 19 columns) full of messy data — blank rows, wrong data types, dates stored as text, numbers stored with commas, inconsistent ratings.

The data was far from clean. Here's what I fixed in powerbi workbench before a single visual was built:
- Removed 98 blank rows + 74 duplicates
- Fixed 'rated' column — same rating in 5 different formats
- Extracted clean year from mixed values like '2011–2016'
- Converted runtime from 'min' (text) → (number)
- Converted 2 date columns with different locale formats etc.

### Project Insights:
- 879 titles across movies, series & episodes
- 463 directors | 813 actors | 14 genres
- IMDB votes mapped by country
- Rating breakdown by genre (Tree-map)
- Content growth from 1920 to 2020

### Conclusion: 
Animation leads on rating. USA & India dominate on votes. Movies make up 77% of all content.
