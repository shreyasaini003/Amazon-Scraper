# Product Details Scraper

This repository contains a Python script that scrapes product details (title and price) from an e-commerce website using the `requests` and `BeautifulSoup` libraries.

## Requirements

- Python 3.x
- `requests` library
- `beautifulsoup4` library
- `lxml` parser

You can install the required libraries using `pip`.

## Usage

1. Clone this repository to your local machine.

2. Navigate to the project directory.

3. Run the script.

4. Enter the product URL when prompted.

## Script Details

The script includes:

- **Headers Configuration**: Custom headers are set to mimic a real browser request.
- **Function to Get Product Details**: Fetches the product title and price from the provided URL and returns them in a dictionary.
- **Error Handling**: In case of any exceptions during scraping, the error is printed out.

This script is useful for quickly extracting product information from a webpage for further processing or analysis.

## Contributing

Contributions are welcome! Please create a pull request or open an issue to discuss any changes.
