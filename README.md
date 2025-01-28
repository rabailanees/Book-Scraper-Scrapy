# Book Scraper with Scrapy

## Overview

This repository contains a **Scrapy** web scraping project that extracts book information from the website **[books.toscrape.com](http://books.toscrape.com/)**. The scraper collects data on books such as titles, prices, ratings, and availability. This project serves as an example of how to use Scrapy for web scraping and data extraction.

## Features

- Scrapes book titles, prices, ratings, and availability.
- Organized Scrapy project structure with spiders and pipelines.
- Includes handling for pagination to scrape multiple pages of books.
- Example of how to run a Scrapy spider and export the data into CSV.

## Requirements

To run this project, you'll need:

- Python 3.x
- Scrapy installed. If not already installed, use the following command to install Scrapy:
  ```bash
  pip install scrapy
  ```

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/book-scraper-scrapy.git
    ```

2. Navigate to the project directory:
    ```bash
    cd book-scraper-scrapy
    ```

3. Install required libraries:
    ```bash
    pip install -r requirements.txt
    ```

## Running the Scraper

To run the Scrapy spider and scrape the data, use the following command:

```bash
scrapy crawl books
```

You can also export the scraped data to a CSV file:

```bash
scrapy crawl books -o books.csv
```

## Directory Structure

- **spiders/**: Contains the Scrapy spiders to scrape data from the website.
- **items.py**: Defines the structure of the data to be scraped.
- **pipelines.py**: Defines how to process the scraped data.
- **settings.py**: Contains project settings for Scrapy.

## License

This project is licensed under the MIT License.
