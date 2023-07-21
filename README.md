# Netflix-movies-and-TV-shows
## README.md
The description of data sources, location and data dictionary for the research project of Netflix movies and TV shows. 

The research data was sourced from Kaggle, by the author [VICTOR SOEIRO](https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies) in July 2022 while the crosschecking data was sourced from Kaggle, by the author [ITISNARAYAN63](https://www.kaggle.com/datasets/narayan63/netflix-popular-movies-dataset) in 2023. 

#
### Data Location
#### Research Data
[Data](https://github.com/huiyi451/Netflix-movies-and-TV-shows/blob/main/research%20original%20data.csv) (data file linked from GitHub Repository) or Data file named 'research original data' in Data folder.

[Cleaned Data](https://github.com/huiyi451/Netflix-movies-and-TV-shows/blob/main/research%20cleaned%20data.csv) or Data file named 'research cleaned data' in Data folder.

#### Crosschecking Data
[Data](https://github.com/huiyi451/Netflix-movies-and-TV-shows/blob/main/crosschecking%20original%20data.csv) or Data file named 'crosschecking original data' in Data folder.

[Cleaned Data](https://github.com/huiyi451/Netflix-movies-and-TV-shows/blob/main/crosschecking%20cleaned%20data.csv) or Data file named 'crosschecking cleaned data' in Data folder.


|  | **Observations** | **Variables**                |
| :------------- | :----- | :---- |
| Research Data | 5851 | 15 |
| Research Data (Cleaned) | 5831 | 9 |
| Crosschecking Data | 9958 | 9 |
| Crosschecking Data (Cleaned) | 5091 | 5 |

#
## Data Dictionary
#### Research Data
All variables in the original research dataset.
| **Variables** | **Description**                |
| :-------- | :------------------------- |
| id | The title ID on JustWatch. |
| title | The name of the title. |
| show_type | TV show or movie. |
| description | A brief description. |
| release_year | The release year. |
| age_certification | The age certification. |
| runtime | The length of the episode (SHOW) or movie. |
| genres | A list of genres. |
| production_countries | A list of countries that produced the title. |
| seasons | Number of seasons if it's a SHOW. |
| imdb_id | The title ID on IMDB. |
| imdb_score | Score on IMDB. |
| imdb_votes | Votes on IMDB. |
| tmdb_popularity | Popularity on TMDB. |
| tmdb_score | Score on TMDB. |

#### Research Data (Cleaned)
The variables that we used in the research.
| **Variables** | **Description**                |
| :-------- | :------------------------- |
| title | The name of the title. |
| show_type | TV show or movie. |
| release_year | The release year. |
| age_certification | The age certification. |
| runtime | The length of the episode (SHOW) or movie. |
| genres | A list of genres. |
| production_countries | A list of countries that produced the title. |
| imdb_score | Score on IMDB. |
| imdb_votes | Votes on IMDB. |

#
#### Crosschecking Data
All variables in the original crosschecking dataset.
| **Variables** | **Description**                |
| :-------- | :------------------------- |
| title | The name of the title. |
| year | The release year. |
| certificate | The age certification. |
| duration| The length of the episode (SHOW) or movie. |
| genre | A list of genres. |
| rating | The rating on IMDB. |
| description | A brief description. |
| stars | The cast of the movie. |
| votes | The number voted by people. |

#### Crosschecking Data (Cleaned)
The variables that we used in the research for crosschecking.
| **Variables** | **Description**                |
| :-------- | :------------------------- |
| title | The name of the title. |
| certificate | The age certification. |
| genre | A list of genres. |
| rating | The rating on IMDB. |
| votes | The number voted by people. |

