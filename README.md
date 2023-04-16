# Top Rated Movies

The Python script provided is an example of web scraping using BeautifulSoup and requests libraries to extract data from IMDb's top-rated movies page. The script sends a GET request to the IMDb website, downloads the HTML content, and parses it using BeautifulSoup. It then searches for the table that contains the movie data and extracts the movie titles, release years, and ratings from the table.

The extracted data is stored in lists and then used to create a dataframe using the pandas library. The dataframe is then saved to an Excel file using the to_excel method, with the filename "top_rated_movies.xlsx" and without including an index column.

The script demonstrates how to use web scraping techniques to extract data from a website and how to manipulate and store the extracted data using pandas. It can serve as a starting point for further customization or integration into larger projects that require data extraction from IMDb or other similar websites for analysis, visualization, or other purposes.

## step-by-step process to create a Python script for web scraping IMDb's top-rated movies and saving the data into an Excel file:
1. Install necessary libraries: Open a terminal or command prompt and install the required libraries: beautifulsoup4, requests, and pandas. You can install them using pip, the Python package manager, by running the following commands:
```text
pip install beautifulsoup4
pip install requests
pip install pandas
```
2. Import required libraries: In your Python script, import the necessary libraries at the beginning of the file.
3. Send a GET request: Use the requests library to send a GET request to the IMDb's top rated movies page and retrieve the HTML content.
4. Parse HTML content: Parse the HTML content using BeautifulSoup and specify the parser (e.g., 'html.parser').
5. Find the table: Use BeautifulSoup's find or find_all methods to locate the table that contains the movie data by inspecting the HTML structure of the IMDb's top rated movies page.
6. Extract data: Extract the desired data from the table. Use BeautifulSoup's methods to navigate the HTML structure and retrieve the movie titles, release years, and ratings.
7. Create a dataframe: Use the pandas library to create a dataframe from the extracted data.
8. Save to Excel: Use the to_excel method to save the dataframe to an Excel file.
9. Run the script: Save the Python script and run it in a Python environment (e.g., Jupyter Notebook, Python IDE, or command line) to execute the web scraping and data saving process.
10. Verify results: After running the script, you should see an Excel file named "top_rated_movies.xlsx" in the same directory as your Python script. Open the Excel file to verify that the extracted data has been saved correctly.
That's it! You have now created a Python script that scrapes IMDb's top-rated movies and saves the data into an Excel file. You can further customize the script to suit your specific needs, such as data cleaning, analysis, visualization, or integration into a larger project.
