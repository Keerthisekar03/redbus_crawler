Python:
•	Python is a widely used general-purpose, high level programming language.
•	It was mainly developed for emphasis on code readability, and its syntax allows programmers to express concepts in fewer lines of code.

Import :
Datetime    - 	Basic date and time types.

Streamlit (st) 
•	Streamlit makes it easy for you to visualize, mutate, and share data. 
•	It transform Python scripts into interactive web apps in minutes, instead of weeks.
•	It build dashboards, generate reports, or create chat apps.

Advantage of streamlit 
•	Quick proof-of-concepts.
•	Data exploration tasks.
•	Projects that demand speed and flexibility.

Selenium 
•	Selenium is an open-source automation testing tool that supports several scripting languages like Python, C#, 
•	Java, Perl, Ruby, JavaScript, etc.,depending on the application to be tested.

Selenium WebDriver 
•	It can be used with Python to create test scripts that interact with web pages and test their functionality. 
•	To utilize Selenium WebDriver with Python, use pip to install the Selenium package.
•	If you have installed Selenium Python bindings, you can start using it from Python like this:
•	from selenium import webdriver  - It also allows you to perform cross browser compatibility testing.
•	from selenium.webdriver.common.by import By - By() Set of supported locator strategies.
•	from selenium.webdriver.chrome.service import Service - A Service class that is responsible for the starting and stopping of chromedriver.
•	from selenium.webdriver.chrome.options import Options - The Chrome.options Class is a concept in Selenium WebDriver for manipulating  various properties of the Chrome driver.
•	from selenium.webdriver.support.ui import WebDriverWait - Constructor, takes a WebDriver instance and timeout in seconds.
•	from selenium.webdriver.support import expected_conditions as EC - An expectation that all of multiple expected conditions is true.

MySQL connector 
import mysql.connector
•	Start by creating a connection to the database. Use the username and password from your MySQL database.
•	It enables Python programs to access MySQL databases.

import psycopg2 
•	It is designed to perform heavily multi-threaded applications that usually create and destroy lots of cursors  and make a large number of simultaneous INSERTS or UPDATES.

cursor = con.cursor() 
•	Allows Python code to execute PostgreSQL command in a database session. 

Function to scrape data - The web scraping process:
•	Identify the target website. Here we use red_bus website to scrape the data.
•	Collect URLs of the target pages.
•	Make a request to these URLs to get the HTML of the page.
•	Use locators to find the information in the HTML.
•	Save the data in a JSON or CSV file or some other structured format.

Chrome options 
chrome_options.add_argument("--headless")  
•	Headless browsers work much faster than regular browsers, since they do not have to load all the content  that contributes to user experience. Due to their high speed, headless browsers are often used for web page testing.
•	It allows the execution of a full version of the browser while controlling it programmatically. They are executed via a command-line interface or using network communication. 
•	This means it can be used in servers without graphics or display, and still, the Selenium tests run!

chrome_options.add_argument("--no-sandbox") 
•	It disables one of Chrome's more important security mechanisms. 
•	This is sometimes necessary for development, for example when you want to redirect stdout to disk and the sandbox would otherwise prevent writing data to the disk.

chrome_options.add_argument("--disable-dev-shm-usage") 
•	It disables using the /dev/shm shared memory file system, which may reduce memory usage during testing.

st.spinner 
•	Temporarily displays a message while executing a block of code. with st. spinner("Please wait..."): do_something_slow()

