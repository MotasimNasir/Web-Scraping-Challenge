# web-scraping-challenge: Mission to Mars

This repository contains the following:

### Web Scraping

The following websites have been scraped using BeautifulSoup, Pandas, and Splinter.:
 
 * [Mars News Site](https://redplanetscience.com/)

 * [JPL Mars Space Images](https://spaceimages-mars.com)

 * [Mars Facts webpage](https://galaxyfacts-mars.com)

 * [Astrogeology site](https://marshemispheres.com/)

Scraping code: [code](Missions_to_Mars/mission_to_mars.ipynb)

### Flask application

Using MongoDB and Flask, a HTML page has been created to display all the information that was scraped from the URLs above.

 * [Scraping code](Missions_to_Mars/scrape_mars.py)

 * [Flask application](Missions_to_Mars/app.py)

 * [HTML page code](Missions_to_Mars/templates/index.html)

The following output is created: [app.png](Missions_to_Mars/screenshot/app.png)