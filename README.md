<p align="center">
    <img src="https://howtolearnmachinelearning.com/wp-content/uploads/2021/04/coursera_machine_learning_ibm.png?raw=true" alt="IBM and Coursera Logos" width="926" height="133"/>
</p>

# Python Project for Data Science

This is the final project for Course 5, _Python Project for Data Science, AI & Development_. Part of IBM Data Analyst Professional Certificate from Coursera. Available here: https://www.coursera.org/programs/jda20232t1-z1hse/professional-certificates/ibm-data-analyst?collectionId=Wxyxq

For this project, we will assume the role of a Data Scientist / Data Analyst working for a new startup investment firm that helps customers invest their money in stocks. Our job is to extract financial data like historical share price and quarterly revenue reportings from various sources using Python libraries and webscraping on popular stocks. We must also look out for any suspicious stock activity. After collecting this data we will visualize it in a dashboard to identify patterns or trends. The stocks we will work with are Tesla, Amazon, AMD, and GameStop.

As a data scientist working for a hedge fund, you will extract the profit data for Tesla and GameStop and build a dashboard to compare the stock price vs the profit for the hedge fund.

There are two hands-on labs on Extracting Stock Data and one assignment to complete.

## Table of Contents

- [Tools](#tools)
- [Deliverables](#deliverables)
- [Stretch Goals](#stretch-goals)
- [Knowledge Acquired](#knowledge-acquired)
  - [Lab 1](#lab-1)
  - [Lab 2](#lab-2)
  - [Final Assignment](#final-assignment)
- [Process](#process)

## Tools

- Python v3.10.13
- Python Web Scraping (Beautiful Soup)
- Python Data Libraries (NumPy, Pandas)
- Data visualization tools
  - y-finance API
    - for stock information
  - matplotlib and plotly
    - for plotting

## Deliverables

- [x] Extracting Stock Data Lab
- [x] Extracting Stock Data with Web Scraping Lab
- [x] Assignment

## Stretch Goals

- [ ] Make the dates for the two graphs the same so the viusalizations can be compared easier

## Knowledge Acquired

### Lab 1

I am using the **y-finance** package to get ticker data on stocks. Then **plot** that data with **MatPlotLib**.

### Lab 2

I am using the **requests** library to get **HTML** data from a website. Then **parsing** the data using **BeautifulSoup**. Afterwards using **Pandas** to convert the data into a usable **DataFrame** to pull out key values from the tables.

### Final Assignment

I am using the **y-finance** package to get ticker data on stocks.

Then use the **requests** library to get **HTML** data from a website. Then **parsing** the data using **BeautifulSoup**. Afterwards using **Pandas** to convert the data into a usable **DataFrame** to pull out key values from the tables. Cleaning the data, such as removing Null/Empty values and symbols from strings. Plotting the two graphs to compare the share price and revenue of TSLA and GME.

## Process

1. Data Collection

- I used Beautiful Soup to collect data.

2. Data Cleaning

- Using Pandas to perform operations to get clean data, such as dropna() and replace(). The clean datasets are paramount to a good analysis.

3. Select relevant data

- Select the columns and rows that are most relevant for us.

4. Plot the data

- Use Matplotlib to graph the relevant data. The visualization makes finding insights easier.
