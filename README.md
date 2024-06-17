# SmithScraper

SmithScraper is a Python project designed to scrape data from the American History section of the Smithsonian website. It uses Beautiful Soup to extract information and save it in a CSV file. The project also includes a proxy checker to verify if a proxy is being used and if it is working.

## Features

- Scrapes titles, images, and topics from the Smithsonian website.
- Saves scraped data in CSV format.
- Checks if a proxy is being used and whether it is working.

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/legaroid/SmithScraper.git
    cd SmithScrape
    ```

2. Install the dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

1. To check if a proxy is being and if it is working, update the `proxies` variable and run the proxy checker code section.

2. To scrape the Smithsonian website, update the `proxies` variable if needed and run the scraper code section.

3. The scraped data will be saved as `data.csv`.

## License

This project is licensed under the MIT License.
