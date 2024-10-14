# Goodreads Choice Awards Scraper and Visualizer

This project scrapes the Goodreads Choice Awards data for the best books of the year, saves the data into a CSV file, and generates a word cloud visualization of the book titles. 

## Table of Contents
> Technologies Used
- Python
- BeautifulSoup
- Requests
- Pandas
- Matplotlib
- Seaborn
- WordCloud

## Project Files

This project contains the following files:

- **cleaned_books.ipynb**: Jupyter notebook for cleaning and processing the scraped book data.
- **goodreads_best_books_scraper.ipynb**: Jupyter notebook for scraping data from the Goodreads Choice Awards page.
- **goodreads_best_books.csv**: CSV file containing the scraped data of the best books from Goodreads.
- **requirements.txt**: Text file listing the required Python packages for this project.
- **word_cloud_book_titles.png**: PNG image file containing the generated word cloud visualization of book titles.

## Usage
> Scrape Data:
Run the goodreads_best_books_scraper.ipynb notebook to scrape data from the Goodreads Choice Awards page and save it to a CSV file.

> Clean Data:
Use the cleaned_books.ipynb notebook for cleaning and processing the scraped book data.

> Generate Visualizations:
After cleaning the data, run the visualization code in the visualize.py script (if applicable) to create visualizations, including a word cloud of book titles.

> Visualization
The generated word cloud will be saved as a PNG image (word_cloud_book_titles.png) in the current directory. You can modify the parameters in the visualize.py file to customize the appearance of the word cloud.
