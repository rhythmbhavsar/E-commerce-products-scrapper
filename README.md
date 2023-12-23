# E-commerce Website Image Scraper


This Python project is designed to scrape images from an E-commerce website, specifically targeting the "Macmerise" website section for iPhone 15 glass cases. The script scrapes the product images, saves them locally, and generates a DataFrame containing image names and their respective paths.

## Introduction

This script utilizes Python along with the Beautiful Soup and Requests libraries to scrape product images from the specified URL. It traverses the HTML structure, extracts images and their associated names, downloads these images, and stores them in a local directory. Moreover, it constructs a DataFrame to manage the metadata of the downloaded images.

![image](https://github.com/rhythmbhavsar/E-commerce-products-scrapper/assets/98228696/455399e5-b678-49e8-b9cd-eac1ba125fdf)


## Features

- Scrapes product images from an E-commerce website.
- Saves images locally for offline access.
- Creates a DataFrame to organize image metadata.


## Usage

1. Run the Python script:

    ```bash
    python scraper.py
    ```

2. Check the `image_folder` directory for downloaded images.
3. View the generated DataFrame containing image metadata.

