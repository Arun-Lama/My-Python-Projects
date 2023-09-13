# Purpose of the Program

The purpose of this program is to automate the process of downloading daily stock price and indices values and store it in a csv file. The code can be run daily to get the daily price updated. In case the date is missed, the program automatically detects the remaining dates to be downloaded. 

# How to Run

Download the Jupyter notebook file and refer to the PriceHistory.csv file within the code. 

# Output CSV Format

![Out CSV Format](https://github.com/Arun-Lama/Nepse-Price_scraping/blob/86331f9673468fceba541bfe868ce9bf055ea5e6/output%20format.png)


# Libraries Used


* `pandas`: Used for data manipulation and working with DataFrames.
* `numpy`: Used for numerical operations.
* `BeautifulSoup` from `bs4`: Used for web scraping HTML content.
* `selenium`: Used for web automation and interaction with web pages.
* `webdriver_manager.chrome`: Used to manage the ChromeDriver.
* `chrome.service.Service` from `selenium.webdriver.chrome.service`: Used for configuring ChromeDriver service.
* `selenium.webdriver.common.by.By`: Used for locating elements on web pages.
* `selenium.webdriver.chrome.options.Options`: Used for configuring ChromeDriver options.
* `calendar`: Used for calendar-related operations.
* `os`: Used for interacting with the operating system.
* `time`: Used for adding delays in the script execution.

# Contributing

If you're interested in contributing to this project, I welcome your input! Whether you want to fix a bug, add a new feature, or improve the code in any way, your contributions are valuable.
