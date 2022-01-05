# Web-Scraping-using-Scrapy-
****
Initial release date: 5 Jan 2022

## Description
The goal of this repository is to scrap the data from the webpage of a product on ecommerce platform like Amazon, Flipkart etc with just few simple lines in python. This jupyter notebook scraps the data of a product on Amazon and save data into csv. 

## Requirements
For Coding the only need is Python. 

* Python 3

Instructions to install Python 3 are [here](https://realpython.com/installing-python/)

## Setup

First, clone or fork this repository. Then to set up your virtual environment, do the following:

1. Create a virtual environment in the root directory: `python -m venv $ENV_NAME`
2. Activate the virtual environment: ` source $ENV_NAME/bin/activate` (for MacOS, Unix, or Linux users) or ` .\ENV_NAME\Scripts\activate` (for Windows users)
3. Install requirements: `pip install -r api/requirements.txt`
4. Set xpath of desired data in response of the product webpage in the parse fuction of AmazonToCsv class  
5. Run run_spider function.

