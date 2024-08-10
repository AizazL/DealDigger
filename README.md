# DealDigger

![DealDigger](https://github.com/user-attachments/assets/272c59c9-f61b-4e30-b741-7974a23369ef)

**DealDigger** is a Python-based Amazon web scraper designed to efficiently scrape and filter Amazon listings based on a user-defined query, search filter, and price filter. The tool returns the filtered data in an Excel sheet, providing a streamlined way to find the best deals.

> **Disclaimer**: This project is now deprecated and is no longer actively maintained. While it may still function, it is recommended to use more up-to-date tools or methods for web scraping as Amazon's website structure and anti-scraping measures may have changed.

## Features

- **Custom Query**: Scrapes Amazon listings based on a specified search query.
- **Filtering Options**: Allows filtering of items based on a keyword or phrase and a specified price range.
- **Excel Export**: Outputs the scraped and filtered data into an Excel sheet for easy review and analysis.

## Technologies Used

DealDigger is built using the following Python libraries:

- **Selenium**: For dynamic web page interaction.
- **BeautifulSoup**: For HTML parsing and data extraction.
- **ChromeDriver**: For automating the Chrome browser.
- **Time**: For managing delays and wait times in the scraping process.
- **Pandas**: For data manipulation and analysis.
- **Openpyxl**: For writing data to Excel files.
- **Numpy**: For efficient numerical operations.

## Getting Started

### Prerequisites

Ensure you have Python installed, and then install the required libraries:

```bash
pip install selenium beautifulsoup4 pandas openpyxl numpy
