# WebshopPriceScraper

## Project Overview

**WebshopPriceScraper** is a Python-based tool designed to automate the process of scraping product prices from popular e-commerce websites such as Amazon, Temu, and others. The goal of the project is to retrieve up-to-date pricing information for products and store it in a structured format for analysis or reporting purposes.

## Features

- **Multi-site support**: Scrape product prices from different e-commerce platforms (Amazon, Temu, etc.).
- **Scalable scraping**: Extendable scraping logic to add support for more websites as needed.
- **Price tracking**: Fetch and store product prices for trend analysis.
- **Data output**: Export scraped data in CSV format for easy use in Excel or other data processing tools.
- **User-defined configurations**: Allow setting custom user-agent and other configurations via settings.

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/WebshopPriceScraper.git
    cd WebshopPriceScraper
    ```

2. **Install dependencies**:
    Make sure you have Python 3 installed on your system, then install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

Once you have the dependencies installed, you can run the scraper by providing the URL of a product from a supported website.

### Example Usage

```bash
python scraper.py
