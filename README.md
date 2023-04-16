# Top-Rated-Movies

The Python script provided is an example of web scraping using BeautifulSoup and requests libraries to extract data from IMDb's top-rated movies page. The script sends a GET request to the IMDb website, downloads the HTML content, and parses it using BeautifulSoup. It then searches for the table that contains the movie data and extracts the movie titles, release years, and ratings from the table.

The extracted data is stored in lists and then used to create a dataframe using the pandas library. The dataframe is then saved to an Excel file using the to_excel method, with the filename "top_rated_movies.xlsx" and without including an index column.

The script demonstrates how to use web scraping techniques to extract data from a website and how to manipulate and store the extracted data using pandas. It can serve as a starting point for further customization or integration into larger projects that require data extraction from IMDb or other similar websites for analysis, visualization, or other purposes.
