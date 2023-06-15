# IMDb Top 250 Movies Web Scraping

![Project Screenshot](https://miro.medium.com/v2/resize:fit:1400/1*gD7Ok6KQpnhpPDPALPb7aQ.png)

## Introduction

This project involves web scraping data for the top 250 movies listed on IMDb. The data is collected using Python, along with the BeautifulSoup library for parsing HTML and extracting the required information. The data extracted is structured into a pandas DataFrame, which makes it easy to analyze and manipulate.

## Tools and Libraries Used

- Python
- BeautifulSoup
- Pandas

Feel free to explore the 👉 [Jupyter Notebook](https://github.com/mudit-mishra8/Imdb-web-scrapping/blob/main/WEBSCRAPPING_IMDB_top_250.ipynb) for the detailed code and data extraction process.

## Data

The data consists of the following columns:

- Name: Title of the movie
- Year: Release year of the movie
- Month: Release month of the movie
- Duration: Runtime of the movie in minutes
- Cast: List of main actors/actresses
- Director: Director of the movie
- Users: Number of users who rated the movie on IMDb
- Production: Production company
- Genre: Genre(s) of the movie
- Budget: Budget of the movie
- US_Canada_Collection: Box office collection in the US and Canada
- Weekend_Collection: Opening weekend box office collection
- Worldwide_Collection: Total worldwide box office collection
- Meta_Score: Metascore of the movie
- Origin_Currency_Symbol: Currency in which the budget and collections are represented
- Rating: IMDb rating of the movie
- Country of Origin: Country where the movie was produced

## Methodology

1. Sent a HTTP request to the URL of the webpage IMDb Top 250 movies to extract the contents of the page.
2. Used BeautifulSoup to parse the HTML content.
3. Extracted the data by traversing the parsed HTML tree structure.
4. Structured the data into a pandas DataFrame.

