# Module-11
Data Collection &amp; Web Scraping
Splinter and HTML parsing with Beautiful Soup
-----------
## Part 1: Scrape Titles and Preview Text from Mars News
1. Use automated browsing to visit the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape.
2. Create a Beautiful Soup object and use it to extract text elements from the website.
3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
    - Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview.
    - Store all the dictionaries in a Python list.
    - Print the list in your notebook.
-----------
## Part 2: Scrape and Analyze Mars Weather Data
1. Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site. Inspect the page to identify which elements to scrape.
2. Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
3. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:
    - id: the identification number of a single transmission from the Curiosity rover
    - terrestrial_date: the date on Earth
    - sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
    - ls: the solar longitude
    - month: the Martian month
    - min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
    - pressure: The atmospheric pressure at Curiosity's location
4. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.
5. Analyze your dataset by using Pandas functions to answer the following questions:
    - How many months exist on Mars?
    - How many Martian (and not Earth) days worth of data exist in the scraped dataset?
    - What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
        - Find the average minimum daily temperature for all of the months.
        - Plot the results as a bar chart.
    - Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
        - Find the average daily atmospheric pressure of all the months.
        - Plot the results as a bar chart.
    - About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
        - Consider how many days elapse on Earth in the time that Mars circles the Sun once.
        - Visually estimate the result by plotting the daily minimum temperature.
6. Export the DataFrame to a CSV file.
-----------
## Reflection
Part 1 of the assignment was very straight forward. I had followed the guide given by our instructor to reference which activities done in class. I found that it was extremely helpful and was able to complete the first part relatively error free.
However, for part 2, still, following the guide given, I needed a lot more support and had help from my classmates, I used askBCS quite a few times, and had my tutor walk me through the questions. It was quite difficult for me to understand at the beginning, as the terminology being used was a little confusing. The section I had the most difficulty with was to create the initial dataframe with Pandas. We had gone over it in class on day 3, with the acitivy 5 and 6, and was quite confident at the start. I replaced the variables from the class activity to correspond with the assignment. I was still getting a few errors, and the dataframe wasn't appearing correctly. I had to finally change "for header in headers" to "for heading in headings". It seems like such a minor change in words, but it is a key factor to collecting data. Overall, it has been very interesting to continue to learn new ways to improve my skills. Having a TA in our group is also very helpful, as a class, we utilize his support very often.
