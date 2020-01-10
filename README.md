# Aggregation Phenomena in Movie Industry

**Team Members: Rui CHEN, Shichao JIA, Jimin WANG, Zhuoyue WANG**

## Requirements

- Python 3
- pandas
- numpy
- networkx 2.3
- pyecharts
- json
- datetime
- math
- seaborn
- matplotlib
- snapshot_selenium
- wordcloud
- nltk
- io
- PIL
- itertools
- scipy
- collections

## Dataset

- ```tmdb_5000_movies.csv```
  - **General data** of 4803 movies with 20 feature columns
    - budget
    - genres
    - homepage
    - id
    - keywords
    - original_language
    - original_title
    - overview
    - popularity
    - production_companies
    - production_countries
    - release_date
    - revenue
    - runtime
    - spoken_languages
    - status
    - tagline
    - title
    - vote_average
    - vote_count
- ```tmdb_5000_credits.csv```
  - **Credits data** of 4803 movies with 4 feature columns
    - movie_id
    - title
    - cast
    - crew

## Jupyter notebook

- ```ntds_tmdb_data_explore.ipynb```
  - **Preprocessing** of original data, mainly including **data cleaning** and **feature augmentation**.
  - **Preliminary data exploration**
- ```ntds_tmdb_movie_graph.ipynb```
  
  - Pipeline of **Movie** **Graph built by similarity of leading actors**, including data preprocessing, network construction, data analysis and visualization.
- ```ntds_tmdb_actor_graph.ipynb```
  
- Pipeline of **Actor Graph built by co-appearance**, including data preprocessing, network construction, data analysis and visualization.
  
- ```ntds_tmdb_crew_graph.ipynb```

  - Pipeline of **Movie Graph built by similarity of main crew**, including data preprocessing, network construction, data analysis and visualization.

    

## Component

- ```chromedriver.exe```
  - This component is to ensure pyecharts work normally in jupyter lab by chrome.