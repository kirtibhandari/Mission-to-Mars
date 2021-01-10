# **Web Scraping :Mission-to-Mars**

## **Project Overview:**
This project is an example of Web Scraping, which means extraction of information from an active website. 
To make the scrape successful, the following have been used herein:
- Chrome developer tools : to identify HTML components to the data we want to extract, which is hemisphere's full resolution images from the url 'https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars' and their titles respectively, and displaying the same under "Mars Hemisphere block".
- Beautiful Soup and Splinter to automate the Web Browser and gather the data we've identified and Python to write the script
- Mongo - a No-SQL database to store the data, which is a list of dictionaries, having key-value pairs of Image URLs and Titles
- Flask : a web application, to display the data we've scraped, using a button where the script for scraping gets executed after the button is clicked on the website. The scraping code , upon execution, visits the website we have specified, scrapes tha data and updates the website with new data.
- Also, some components of Bootstrap have been used for styling and making it device screen size responsive.

**Website , before scrape:**

![](https://github.com/kirtibhandari/Mission-to-Mars/blob/main/Resources/Before_Scraping.png)

**After Scrape button is clicked:**

![](https://github.com/kirtibhandari/Mission-to-Mars/blob/main/Resources/Scraping_success.png)

**Website, after successful scraping:**

![](https://github.com/kirtibhandari/Mission-to-Mars/blob/main/Resources/After_Scraping.png)
