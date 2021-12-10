# Mission-to-Mars

## Overview
The purpose of this project was to take images of Mars from a website, scrap it, and then add those images to my own webpage.

## Tools
To make this project possible, multiple tools and languages were used, the most notable being:
- BeautifulSoup
- Splinter
- Pandas
- Webdriver Manager
- Python
- HTML/CSS/Bootstrap
- MongoDB

## Process
Using Splinter and BeautifulSoup, I visited a Mars NASA news site that was scrapper-friendly. From that site, I scrapped news titles, Mars images, and image labels from the site into a list of dictionaries to later display on my HTML page. I also scraped a Mars fact site to scrape information about Mars into a Pandas DataFrame to be embedded into my HTML page. All of the data that was scraped was added to a Mongo database to be utilized by Flask in order to properly display the Mars information and images on our HTML page. After using Bootstrap elements to clean up the page, I was left with a webpage that would scrape and display Mars data and images from other pages onto my own.
