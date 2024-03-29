# Background

Ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup.
You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.
As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, 
organizing and storing data, analyzing data, and then visually communicating your insights

#  What You're Creating

This new assignment consists of two technical products. You will submit the following deliverables:
Deliverable 1: Scrape titles and preview text from Mars news articles.
Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

# NOTE
All the work for mars_news and mars_weather are in the folder mars_challenge.

# Instructions

Part 1: Scrape Titles and Preview Text from Mars News

Open the Jupyter Notebook in the starter code folder named part_1_mars_news.ipynb. You will work in this code as you follow the steps below to scrape the Mars News website.
Use automated browsing to visit the Mars news site Links to an external site.. Inspect the page to identify which elements to scrape.
Create a Beautiful Soup object and use it to extract text elements from the website.
Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview
Store all the dictionaries in a Python list.
Print the list in your notebook.
Optionally, store the scraped data in a file (to ease sharing the data with others). To do so, export the scraped data to a JSON file.
Used starter code file part_1_mars_news.ipynb. Exported mars_news to mar_news.json file. I imported json function to export the file.

# Part 2: Scrape and Analyze Mars Weather Data

Open the Jupyter Notebook in the starter code folder named part_2_mars_weather.ipynb. You will work in this code as you follow the steps below to scrape and analyze Mars weather data.
Use automated browsing to visit the Mars Temperature Data Site Links to an external site.. Inspect the page to identify which elements to scrape. 
Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.

Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:
id: the identification number of a single transmission from the Curiosity rover
terrestrial_date: the date on Earth
sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
ls: the solar longitude
month: the Martian month
min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
pressure: The atmospheric pressure at Curiosity's location
Examine the data types that are currently associated with each column. If necessary, cast (or convert) 
the data to the appropriate datetime, int, or float data types.Used starter code file part_2_mars_weather.ipynb
 Exported mars_weather table to mars_weather.csv.

# Hints, Work and Help
I went through all class materials, understating different visualization, panda function and check my code in xpert learning. 
Did lot of research in different panda function in web. Used srtarter code. 
