# TripAdvisor Restaurant Rating Analysis

## Data Folder
The `data`, `models`, `images` folders in the Google Drive link below are to be placed at the same level as the notebooks in this repository.

Google Drive Link: 

## Dependency List

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
