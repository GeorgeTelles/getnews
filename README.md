<div>
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_clara.png" alt="logo clara" width="300" style="display: inline-block; vertical-align: top; margin-right: 10px;">
  <img src="https://raw.githubusercontent.com/GeorgeTelles/georgetelles/f69531ec6b293b5148563588a764c010015d315e/logo_dark.png" alt="logo dark" width="300" style="display: inline-block; vertical-align: top;">
</div>

# News Extraction - Globo.com

This project is a Python application that performs news extraction from the main page of the Globo.com website. The goal is to capture the titles and links of the highlighted news articles on the homepage and display them in an organized manner.

## Functionality

The Python script performs the following tasks:

1. **HTTP Request**: Uses the `requests` library to send an HTTP GET request to the main page of the Globo.com website.
2. **HTML Parsing**: Parses the HTML content of the page using the `BeautifulSoup` library from `bs4`.
3. **Data Extraction**: Searches for all `<a>` elements on the page and filters those containing news titles, identifying them by their specific CSS classes.
4. **Dictionary Creation**: Stores the news titles and their corresponding links in a dictionary.
5. **Display**: Prints the titles and links of the news articles in a readable format in the console.

## Requirements

- Python 3.x
- Libraries: `requests`, `beautifulsoup4`

