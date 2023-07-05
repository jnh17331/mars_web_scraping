# mars_web_scraping

This new assignment consists of two technical products. You will submit the following deliverables:

    Deliverable 1: Scrape titles and preview text from Mars news articles.

    Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.


## Deliverable 1:
In this jupyter notebook, we get a list of dictionaries that hold the title and a preview of Mars articles written by NASA off of an imitation site. Below is an example of the output from the scraped data:

  ```python
  {'title': "NASA's MAVEN Observes Martian Light Show Caused by Major Solar Storm", 
   'preview': "For the first time in its eight years orbiting Mars, NASA’s MAVEN mission witnessed two different types of ultraviolet aurorae simultaneously, the result of solar storms that began on Aug. 27."
  }
  ```

## Deliverable 2:
In this jupyter notebook, we scrape data from a table; filled with mars facts, from a website using splinter and pandas. We use this table to answer and visualize the following questions:

1. How many months exist on Mars?
2. How many Martian (and not Earth) days worth of data exist in the scraped dataset?
3. What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
    * Find the average the minimum daily temperature for all of the months.
    * Plot the results as a bar chart.
4. Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
    * Find the average the daily atmospheric pressure of all the months.
    * Plot the results as a bar chart.
5. About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
    * Consider how many days elapse on Earth in the time that Mars circles the Sun once.
    * Visually estimate the result by plotting the daily minimum temperature.
