# Sofifa Scraper

Scrapes FIFA Player Ratings from sofifa.com

> Note: Please do not use this script to overload sofifa.com server

## Installing Requirements

    $ pip3 install -r requirements.txt

## Execution

* -f or --filename to pass output file name argument. Default value is output.csv.
* --max_pages to pass the maxmimum number of pages to scrape. Default value is 25.
* --year or -y to pass the FIFA release year. Currently, data from year 2007 are available.

Examples:

    $ python scrape_sofifa.py --max_pages 5 --filename data.csv

    $ python scrape_sofifa.py -f data.json

    $ python scrape_sofifa.py --filename data.json --year=2007

## Help

    $ python scrape_sofifa.py --help

    $ python scrape_sofifa.py -h