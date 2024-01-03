# Amazon Web Scraper

This project is a simple web scraping script using Python and BeautifulSoup to track the price of a specific product on Amazon. The script fetches the product title, price, and date, and stores the data in a CSV file. Additionally, it checks if the price falls below a certain threshold and sends an email notification.

## Table of Contents

- [Features](#features)
- [Getting Started](#getting-started)
-[Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)

## Features

- Web scraping of Amazon product details (title, price, date).
- Data storage in a CSV file.
- Price threshold checking with email notification.

## Getting Started

### Prerequisites

- Python 3.x
- Required Python libraries (install using `pip install -r requirements.txt`):
  - bs4 (BeautifulSoup)
  - requests
  - pandas

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/Moharabie99/Amazon-Web_Scraper.git
   cd Amazon-Web_Scraper
install the required library:   
pip install -r requirements.txt
### Usage
1. Run the main script to start monitoring and scraping the product price
python scraper.py
2. The script will fetch the product details and store them in AmazonWebScraperDataset.csv. It will also check if the price falls below $15 and send an email notification if true.
### Configuration
- To change the product being tracked, update the URL variable in scraper.py with the desired Amazon product URL.
- Adjust the price threshold in scraper.py if needed.


