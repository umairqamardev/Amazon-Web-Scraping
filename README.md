# Amazon-Web-Scraping

Overview

  This project is focused on scraping product information, including titles and prices, from Amazon. The goal is to automate the process of tracking price fluctuations over time and storing   the data in a CSV file for further analysis.
  
  Web Scraping: Extracts product details such as title and price from Amazon product pages using BeautifulSoup and requests.
  Automated Price Tracking: Runs daily, scraping the product data and appending it to a CSV file to keep track of changes over time.
  Data Storage: Saves the product title, price, and the date of extraction into a CSV file, creating a historical record for price analysis.
  Data Reading: The stored data can be easily read and analyzed using tools like pandas.

How It Works

  Scraping: The script scrapes product details by sending an HTTP request with custom headers and parsing the HTML content to extract the required information.
  Data Logging: The extracted data is saved in a CSV file, with new entries being appended after every run.
  Automation: A loop runs the script daily, automating the process of scraping and storing the product data regularly.

Lessons Learned

  Web Scraping: Mastered the use of Python libraries to efficiently scrape data from web pages.
  Data Automation: Learned how to automate tasks to ensure consistent data collection over time.
  Handling Dynamic Content: Managed common web scraping challenges, such as dynamic content and request headers.
  Data Storage and Analysis: Gained experience in storing scraped data in CSV format and analyzing it for trends using tools like pandas.
