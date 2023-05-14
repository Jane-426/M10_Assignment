# M10_Assignment

This repository contains the code and files for the M10 Assignment, which is part of the Data Science Programming III course at NYU. The assignment involves creating a web scraper to parse a table from the Charities Bureau Website and storing the data in an s3 bucket using Python and Selenium.

## Dependencies

The following dependencies are required to run the code:
· Python 3.6+
· pandas
· selenium
· awscli
· boto3
· Google Chrome webdriver
## Files

This repository contains the following files:

· M10_webscraper_assignment.ipybn: the Python notebook that contains the web scraping script
· charities_bureau_scrape_cleaned.csv: the cleaned CSV file of the scraped data
· README.md: this file
## Scripts

The main script for this assignment is M10_webscraper_assignment.ipybn. The script performs the following tasks:

1. Uses Selenium to scrape the Charities Bureau Website
2. Stores the data in a pandas DataFrame
3. Cleans the DataFrame by removing the first row
4. Saves the cleaned data to a CSV file
5. Uploads the CSV file to an s3 bucket
## Usage

To run the script, make sure all dependencies are installed and the Google Chrome webdriver is installed and in your system path. Then, open M10_webscraper_assignment.ipybn in Jupyter Notebook and run all cells. Make sure to update the script with the name of your s3 bucket before running it.

## S3 Bucket

The output CSV file is stored in an s3 bucket named yuchenjibucket. The s3 bucket is set to public so that the file can be accessed by anyone with the link. You can access the file at this link: https://yuchenjibucket.s3.amazonaws.com/charities_bureau_scrape_cleaned.csv.

## Images

The images folder contains an image of the s3 bucket with the output CSV file.
