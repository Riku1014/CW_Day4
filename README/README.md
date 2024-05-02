# Web Scraping Examples

This repository contains two Python scripts for web scraping data from different websites.

## `top_250_movies_imdb.py`

This Python script scrapes data from the IMDb website to retrieve the top 250 movies based on user ratings. It uses the `requests` library to send a GET request to the IMDb top movies page and `BeautifulSoup` to parse the HTML content. The script then extracts the movie titles and prints the top 250 movies.

### How to Use

1. Ensure you have Python installed on your system.
2. Install the required libraries using pip:

pip install requests beautifulsoup4 pandas

3. Run the script:



python top_250_movies_imdb.py


## `us_states_population_wikipedia.py`

This Python script scrapes data from the Wikipedia page listing the states and territories of the United States along with their populations. It retrieves the state names and populations from the table on the page. The script uses the `requests` library to send a GET request to the Wikipedia page and `BeautifulSoup` to parse the HTML content. It then extracts the state names and populations from the table and prints them.

### How to Use

1. Ensure you have Python installed on your system.
2. Install the required libraries using pip:

pip install requests beautifulsoup4
3. Run the script:

