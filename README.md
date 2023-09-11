Scraping Data from Sharesansar
The program then scrapes data from sharesansar.com starting from the day after the latest available data.

It uses Beautiful Soup to parse the HTML content of the website.
Selenium is employed to interact with the web page, enter dates, and retrieve data.
The program excludes data for Fridays and Saturdays.
Downloading Index Data
The program also downloads various indices data from Sharesansar, including sectors like Nepse Index, Banking SubIndex, and others. It collects data for the specified date range.

Usage
Ensure you have the required Python libraries installed, such as pandas, numpy, BeautifulSoup, and Selenium.
Modify the PriceHistory.csv file path as needed in the code.
Run the script, and it will automatically fetch and merge the data.
Contributing
Feel free to contribute to this project by improving the code or adding new features. Create a pull request or open an issue for discussion.

License
This project is licensed under the MIT License.

Note: Respect the terms and conditions of sharesansar.com and any applicable data usage policies while using this program.

Completed by Arun Lama
