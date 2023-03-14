# Mars_Scraping_Challenge

## Project Overview
This project involved scraping data from the web and pulling it into a Pandas dataframe for analysis. The result is two technical deliverables:
  - Mars_news, a notebook that scrapes titles and preview text from Mars news articles.
  - Mars_weather, a notebook that scrapes and analyzes Mars weather data.

### Technologies
Python
Beautiful Soup
Pandas
Matplotlib

## Methods
### Web Scraping
The mars_news notebook uses Beautiful Soup to create an object and extract the titles and preview text of the news articles from https://static.bc-edx.com/data/web/mars_news/index.html.

The mars_weather notebook uses Beautiful Soup to create an object and scrape the data in the HTML table from https://static.bc-edx.com/data/web/mars_facts/temperature.html. The scraped data was assembled into a Pandas DataFrame, which was then cast to the appropriate data types.

### Data Analysis
The Pandas functions were used to analyze the dataset by answering the following questions inside the mars_weather notebook:
  - How many months exist on Mars?
  - How many Martian (and not Earth) days worth of data exist in the scraped dataset?
  - What are the coldest and the warmest months on Mars (at the location of Curiosity)?
  - Which months have the lowest and the highest atmospheric pressure on Mars?
  - About how many terrestrial (Earth) days exist in a Martian year?

### Exporting the DataFrame
The final Pandas DataFrame was exported into a CSV file.

Author: Lacey Morgan
