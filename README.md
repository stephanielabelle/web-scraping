# Web-Scraping
## Module 11 Challenge

This project has two parts, and it utilizes Splinter for web browser automation and Beautiful Soup for parsing of HTML data.  

### Part 1: Scraping Titles and Preview Text from Mars News Website
Jupyter Notebook file: [part_1_mars_news.ipynb](part_1_mars_news.ipynb)  
Using Splinter for automated browsing, visited the [Mars News Site](https://static.bc-edx.com/data/web/mars_news/index.html) and extracted article titles and previews.  
Article titles and previews were exported as a JSON file named [mars_articles.json](Resources/mars_articles.json), available in this repository's Resources folder.

### Part 2: Scraping Mars Weather Data
Jupyter Notebook file: [part_2_mars_weather.ipynb](part_2_mars_weather.ipynb)  
Using Splinter for automated browsing, visited the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html) and scraped the table information into a Pandas Dataframe.  
The Dataframe is available as a csv file named [mars_data](Resources/mars_data.csv), and is located in this repository's Resources folder.  
The data was analyzed to determine:
1. How many datapoints per Mars month in the dataset
2. How many martian days of data exist in the dataset
3. Average minimum daily temperatures by Mars month
4. Average atmospheric pressure by Mars month
5. How many Earth days exist in one Martian year
