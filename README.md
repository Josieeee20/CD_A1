# The introduction of the dataset
The data is extracted from 780 Hollywood films spanning from 1970 to 2014 which includes movie names, character information, line information, etc. This study presents the percentage of white people in all actors to show culture inequelity in vedio works.

## Variables_table_1
| Variable              | Description                                     | DataType           |
| --------------------- | ----------------------------------------------- | ------------------ |
| X                     | Record number                                   | Integer           |    
| CHARACTER_ID          | Unique identifier for characters                | Character       |
| SCRIPT_ID             | Identifier for the movie script                 | Character       |
| CHARACTER_NAME        | Name of the character                           | String             |
| ACTOR_NAME            | Name of the actor                               | String             |
| PARTIAL_MATCH         | Indicator for partial matching                  | Boolean            |
| GENDER                | Gender of the character                         | Percentage       |     
| CHARACTER_RACE        | Race of the character                           | Percentage        |
| ACTOR_RACE            | Race of the actor                               | Percentage        |
| AGE                   | Age of the character                            | Integer            |
| EXTRACTED_WORDS       | Number of words extracted                       | Integer           |
| POLYGRAPH_WORDS       | Words related to polygraph                      | String             |
| IMDB_ACTOR_HOMEPAGE   | Actor's homepage on IMDB                        | String        |
| GOOGLE_IMAGE_SEARCH   | Results from Google Image Search                | String        |


The quantitative data mainly focus on  recording various information about the characters in the movie and the actors who played those roles, including gender, age, race, text analysis, etc.

##  Variables_table_2
| Variable  | Description                   | DataType          |
| --------- | ----------------------------- | ------------------ |
| NUMBER    | Record number                 | Integer           |
| SCRIPT_ID | Unique identifier for movie scripts | Character       |
| IMDB      | IMDB identifier for the movie | Character       |
| TITLE     | Title of the movie            | String             |
| YEAR      | Release year of the movie     | Integer            |
| GROSS     | Gross revenue of the movie    | Integer            |
| GENRE     | Genre of the movie            | String             |
| AWARD     | The number of the award       | Integer            |
| NOTES     | Additional notes              | String             |


This table is used to record basic information about different movies, including the name of the movie, year of release, box office revenue, genre, etc.

# Information about the creator and source of the dataset
The author of this data set are Svaikovsky, Victoria; Meisner, Anne; Kraicer, Eve; Sims, Matthew from McGill University. 
# The source of the dataset
https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/KERZQY
