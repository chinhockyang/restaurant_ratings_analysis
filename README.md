# Restaurant Rating Analysis
This project aims to conduct analysis on data collected from TripAdvisor, using Machine Learning and Natural Language Processing methods to study factors that could improve a restaurant's performances in Singapore.

The information below outlines the steps that are required in order to run the files in our repository.

## Additional Folders required
The `data` and `models` folders are required to use our notebooks. They are provided in the Google Drive link below:
https://drive.google.com/drive/folders/1Ha1sV-vQFdhpOTLZcuZnDSBNLS6wdI-l?usp=sharing

The folders are to be placed at the same level of the notebooks as shown below:
<p align="left">
		<img src="https://github.com/chinhockyang/restaurant_ratings_analysis/blob/master/image/project-directory.png?raw=true" alt="IMAGE ALT TEXT HERE" width="280" border="10" />
</p>

## API Tokens Required
- The file <strong>05_scrape_train_stn_walk_distance</strong> requires the use of an Openrouteservice token to perform geocoding. A free account can be created from 'https://openrouteservice.org/dev/#/login to obtain an ORS API token.
- The files <strong>05_scrape_train_stn_walk_distance</strong>, <strong>06_feature_engineering</strong>, <strong>07_EDA_restaurant_region</strong> and <strong>07_EDA_walking_distance_and_within_mall</strong> require the use of a Mapbox token to perform geospatial visualisation. A free account can be created from on 'https://account.mapbox.com/signup/' to obtain a Mapbox token.


## Virtual Environment and Libraries Required

This project uses Anaconda Virtual Environment to manage project dependencies.

#### Basic Libraries
| Libarary | Purpose | Installation |
| :------------- |:------------- |:-------------|
| Python | | `conda install python` |
| Pandas | | `conda install pandas` |
| Numpy | | `conda install numpy` |
| Scikit-Learn | Machine Learning | `conda install -c anaconda scikit-learn ` |
| GeoPandas | Geospatial Analysis | `conda install --channel conda-forge geopandas` |
| Regex | Regular Expression | `conda install -c anaconda regex` |

#### Data Visualisation
| Libarary | Purpose | Installation |
| :------------- |:------------- |:-------------|
| Seaborn | Data Visualisation | `conda install -c anaconda seaborn` |
| Plotly Express | Data Visualisation | `conda install -c plotly plotly_express` |
| nbformat | Data Visualisation on Notebook | `conda install -c conda-forge nbformat` |
| Python Kaleido | Plotly Dependency | `conda install -c conda-forge python-kaleido` |
| Dython | Visualisation Toolkit | `conda install -c conda-forge dython` |

#### Web Data Extraction
To project uses Selenium to perform Web Scraping from TripAdvisor. To run the scraping notebooks in this directory, 
please download and configure a Chromedriver from this link: https://chromedriver.chromium.org/downloads

| Libarary | Purpose | Installation |
| :------------- |:------------- |:-------------|
| Selenium | Web Mining | `conda install -c conda-forge selenium`|
| Requests | Web Scraping | `conda install -c anaconda requests` |
| BeautifulSoup4 | Web Scraping | `conda install -c anaconda beautifulsoup4`|
| FuzzyWuzzy | String Matching | `conda install -c conda-forge fuzzywuzzy` |
| Openrouteservice | Geocode Walking Path between Locations | `conda install -c michaelsjp openrouteservice` |

#### NLP (Natural Language Programming)
| Libarary | Purpose | Installation |
| :------------- |:------------- |:-------------|
| NLTK | Natural Language Processing | `conda install -c anaconda nltk` |
| WordCloud | NLP Visualisation | `conda install -c conda-forge wordcloud` |
| TextBlob | Sentiment Analysis | `conda install -c conda-forge textblob`|
| Gensim | Topic Modelling | `conda install -c anaconda gensim`|
| pyLDAvis | NLP Visualisation | `conda install -c conda-forge pyldavis`|
