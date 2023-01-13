# Amazon-Web-Scraper
Scrapes and filters Amazon listings based on a query, search filter, and price filter. Returns data in an excel sheet.
Programmed in Python, utilizing the following libraries:

   - Selenium
   - BeautifulSoup
   - ChromeDriver
   - Time
   - Pandas
   - Openpyxl
   - Numpy
   
Simply change the link provided to the SearchResults() function with the query from Amazon you want to scrape all the pages of.

Change the itemFilter and priceFilter variables at the bottom of the page in order to:
  1) Only include items with a keyword or phrase 
  2) Only include items in a certain price range
