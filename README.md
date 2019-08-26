# Studying Terroir

### Introduction

In this repository, we use the wine embeddings built in https://github.com/RoaldSchuring/wine_recommender to explore variations in flavor profile that can be attributed to terroir.

This repo consists of a couple of different files:

- Investigating Terroir Data Prep.ipynb: this notebook file retrieves data from multiple external sources for weather, soil and altitude for the wines in our dataset.
- Investigating Terroir.ipynb: this notebook is used to aggregate the data retrieved in the file above, and subsequently model how terroir attributes help explain the variation in wine embeddings (proxy for flavor profile)

The wine embedding data obtained from the web scraping exercise was too large to be added to this repository. However, the scraper used to mine the raw data from www.winemag.com is available in this GitHub respository: https://github.com/RoaldSchuring/studying_grape_styles. The repository at https://github.com/RoaldSchuring/wine_recommender will explain how these can be converted into wine embeddings. 

### Technologies

- Python
- Jupyter Notebook
- The necessary Python package versions needed to run the various files in this repository have been listed out in the accompanying requirements.txt file

### Project Description

A central concept to the study of wine is terroir: the environmental factors that contribute towards how a wine tastes. There are a lot of myths about terroir in the wine community. Books have been written about whether terroir is even a valid concept to begin with, and scientists have tried to unpack which components of terroir impact flavor profile.

In this repository, we use data science techniques to learn which components of terroir, if any, have an impact.

### Getting Started

1. Clone this repo.

2. Run the web scraper available in https://github.com/RoaldSchuring/studying_grape_styles to get a full and fresh set of wine reviews.

3. Use instructions listed in https://github.com/RoaldSchuring/wine_recommender to convert the wine text descriptions to wine embeddings.

4. Run Investigating Terroir Data Prep.ipynb to pull data on the soil, weather and elevation of the wines scraped from step 3. Make sure to enter your own Google Cloud API key.

5. Run Investigating Terroir.ipynb to explore the relationship between terroir variables and wine flavors.

### Authors

Roald Schuring
