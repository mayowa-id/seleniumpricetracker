# seleniumpricetracker

Automated E-commerce Price Tracker
This is a Java application that can track product prices on an e-commerce website like Amazon, eBay, or any local online store.
The program will use Selenium to scrape product details (name, price, and availability) at regular intervals and notify
the user when the price drops below a specified threshold.


User Input in Driver class :

URL of the product.
Desired price threshold.

Data Extraction:
Uses Selenium to navigate to the product page and scrape the price, product name, and stock status.

Scheduling:
Check the price at regular intervals (e.g., once a day or every few hours).

Notifications:
Print notifications in the console or send an email(future update) when the price drops below the threshold.

Logging:
Log the price changes over time in a file.

Tools & Libraries
Selenium WebDriver: For web scraping.
JSoup (optional): For parsing the HTML if Selenium retrieves the raw HTML source.
Java Mail API: To send email notifications.
JSON / CSV Library: To save price history data.


HOW TO IMPLEMENT: 

1. Setup Selenium:
Install the Selenium WebDriver for Java.
Configure the browser driver (e.g., ChromeDriver, GeckoDriver).

2. Scrape Data:
Navigate to the product page.
Locate and extract the product name, price, and availability using XPath or CSS selectors.

3. Store and Compare:
Save the current price in a file or database.
Compare it with the user-defined threshold.

3. Trigger Notifications:
If the price drops, log message in console or send an email.

