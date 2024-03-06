# Web-scraping-challenge

**Background**

As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

**What You're Creating**

This new assignment consists of two technical products. You will submit the following deliverables:

	a. Deliverable 1: Scrape titles and preview text from Mars news articles.

	b. Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

**Instructions**

**Part 1: Scrape Titles and Preview Text from Mars News**

Open the Jupyter Notebook in the starter code folder named part_1_mars_news.ipynb. You will work in this code as you follow the steps below to scrape the Mars News website.

1. Use automated browsing to visit the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape.

2. Create a Beautiful Soup object and use it to extract text elements from the website.

3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:

	a. Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. An example is the following:

	b. Store all the dictionaries in a Python list.

	c. Print the list in your notebook.

4. Optionally, store the scraped data in a file (to ease sharing the data with others). To do so, export the scraped data to a JSON file. (Note: there will be no extra points for completing this.)

**Part 2: Scrape and Analyze Mars Weather Data**

Open the Jupyter Notebook in the starter code folder named part_2_mars_weather.ipynb. You will work in this code as you follow the steps below to scrape and analyze Mars weather data.

1. Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.

2. Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.

3. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:

	a. id: the identification number of a single transmission from the Curiosity rover

	b. terrestrial_date: the date on Earth

	c. sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars

	d. ls: the solar longitude

	e. month: the Martian month

	f. min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)

	g. pressure: The atmospheric pressure at Curiosity's location

4. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.

5. Analyze your dataset by using Pandas functions to answer the following questions:

	a. How many months exist on Mars?

	b. How many Martian (and not Earth) days worth of data exist in the scraped dataset?

	c. What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:

		i. Find the average minimum daily temperature for all of the months.

		ii. Plot the results as a bar chart.

	d. Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:

		i. Find the average daily atmospheric pressure of all the months.

		ii. Plot the results as a bar chart.

	e. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:

		i. Consider how many days elapse on Earth in the time that Mars circles the Sun once.

		ii. Visually estimate the result by plotting the daily minimum temperature.

6. Export the DataFrame to a CSV file.










