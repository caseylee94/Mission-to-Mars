# Mission-to-Mars

## Project Overview
Robin's web app is looking good and functioning well, but she wants to add more polish to it. She had been admiring images of Mars’s hemispheres online and realized that the site is scraping-friendly. She would like to adjust the current web app to include all four of the hemisphere images. To do this, you’ll use BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images.

Note: The above project overview was extracted from the background to the module 10 Challenge.

## Resources
Data Sources: https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars

Code Files: Mission_to_Mars_Challenge.ipynb, Mission_to_Mars_Challenge.py, Mission_to_Mars.ipynb

Software/Libraries: Visual Studio Code 1.56.0, jupyter Notebook 6.3.0, Jupyter lab 3.0.14, Flask 1.1.2, Splinter 1.26.4, Web Drive Manager, Beautiful Soup, Pymongo, MongoDB 4.4.6, Mongo DB Compass, htmlslib, lxml.

## Project Results
The results for the scraped hemisphere images and urls are shown below:
![img_urls](/Resources/img_urls.png)

I ran into problems executing the code to scrape the images and add them to the website for Robin. I am still in the process of trouble shooting; I believe my code is correct and it was once running without errors but I am now having trouble with my path system in regards to Google Chrome web driver. If there is any feedback regarding this issue or my code in other areas I would appreciate it.
