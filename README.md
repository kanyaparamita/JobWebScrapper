# Web Scraping Job Vacancies

## Introduction

In this project, we built a web scraper to extract job listings from a popular job search platform. We extracted job titles, companies, locations, job descriptions, and other relevant information. Currently, this code is only tailored to scrape jobs from LinkedIn website.

Here are the main steps that were taken in this project:

1. Setup our development environment
2. Understand the basics of web scraping
3. Analyze the website structure of our job search platform
4. Write the Python code to extract job data from our job search platform
5. Save the data to a CSV file
6. Test our web scraper and refine our code as needed

## Prerequisites

Before starting this project, we already have some **basic knowledge of Python programming and HTML structure**. In addition, the **following Python packages** is needed to run the code:

- selenium
- requests
- BeautifulSoup
- mtranslate
- langdetect
- pandas
- csv

We choosed Google Chrome feature of Selenium, so we also also need a **ChromeDriver executable** to run the code. To get the ChromeDriver executable, we need to download it from the official [ChromeDriver website](https://sites.google.com/chromium.org/driver/). 

Some of these packages may or may not have been installed in your local computer environment, however if you'd like to install additional packages that are not included in this environment or are working off platform you can install additional packages using `!pip install packagename` within a notebook cell such as:

- `!pip install selenium`
- `!pip install requests`
- `!pip install beautifulsoup4`

We also need an **url of LinkedIn public job search result web page** specificied [this webpage](https://www.linkedin.com/jobs/search?position=1&pageNum=0) in which you can also add any filter to it (i.e. [link](https://www.linkedin.com/jobs/search?keywords=Docent&location=Amsterdam%2C%20North%20Holland%2C%20Netherlands&geoId=102011674&trk=public_jobs_jobs-search-bar_search-submit&position=1&pageNum=0) for Teachers in Amsterdam). With this public job search feature, you don't have to sign in to any LinkedIn account.

Last but not least, we analyzed the web page structure to get the **specific HTML elements and its attributes** that contain the information we want to extract from the web page.

## Code

Code can be seen in `job_webscrapping.ipynb` Jupyter notebook file.