# IMDb Top 250 Movies Scraper

This project is a Python script that scrapes data for the top 250 movies from the IMDb website. It extracts key information such as title, rating, genre, duration, and more, and saves it into a CSV file.

## Features

*   Scrapes the IMDb Top 250 movies page.
*   Extracts movie title, description, rating value, vote count, content rating, genre, duration, and IMDb link.
*   Converts ISO 8601 duration format to a human-readable string.
*   Saves the extracted data to a CSV file.

## Requirements

*   Python 3.x
*   `requests` library
*   `beautifulsoup4` library
*   `pandas` library

You can install the required libraries using pip:

```bash
pip install requests beautifulsoup4 pandas
```

## Files

*   `IMDb_Top_250_Movies_Scraping.ipynb`: The main Python script for scraping.
*   `top_movies.csv`: The output CSV file containing the scraped movie data.

## License

This project is licensed under the Apache License Version 2.0 - see the [LICENSE](LICENSE) file for details.

