Web Scrape News Headlines
Web-Scraper-for-news-headlines

Problem Statement
Manually collecting news headlines from websites is time-consuming and inefficient. The goal of this project is to automate the process of extracting top news headlines from a public news website and store them in a structured text file.

Objective
Scrape top headlines from a news website

Extract relevant title data from HTML

Store the headlines in a .txt file

Automate data collection using Python

Technologies Used
Python

requests – for sending HTTP requests

BeautifulSoup – for parsing HTML

File handling (.txt) – for saving output

How to Run the Project
Step 1: Install Dependencies

pip install requests beautifulsoup4

Step 2: Run the Script

python news_scraper.py

Step 3: Check Output

After execution, open:

headlines.txt

to view the scraped headlines.

Output
The output file contains numbered news headlines like:

Global markets react to economic changes
New scientific breakthrough announced
Political leaders attend summit
Key Learning Outcomes :
Understanding web scraping basics

Working with HTTP requests

Parsing HTML using BeautifulSoup

Automating data extraction

Writing data to files in Python

Future Improvements :
Export data to CSV or Excel

Add date and timestamp

Scrape specific categories (sports, tech, etc.)

Handle dynamic websites using Selenium

Schedule automatic scraping

Conclusion :
This project demonstrates how Python can be used to automate data collection from public websites efficiently. It provides a foundation for more advanced web scraping and data analysis tasks.
