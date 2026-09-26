🔎 Data Engineer Jobs Scraper
📌 Project Overview

This project uses Python and Selenium to scrape real job listings for Data Engineer positions from the Naukrigulf job portal.

The scraper navigates through the first three pages of search results, collects detailed information about each job listing, and saves the extracted data into a structured CSV file.

🎯 Objectives
Automate web browsing using Selenium
Search for Data Engineer job listings
Navigate dynamically through multiple pages
Extract relevant job information
Store the collected data in a structured CSV file
📊 Data Collected

For each job listing, the following information is extracted:

Job Title
Company Name
Job Location
Required Experience
Full Job Description
🛠️ Technologies Used
Python
Selenium
CSV
📁 Project Structure
Data-Engineer-Jobs-Scraper/
│
├── scraper.py
├── Data_Engineer_Jobs.csv
└── README.md
⚙️ How It Works
Selenium opens the Naukrigulf job portal.
The scraper searches for Data Engineer positions.
It navigates through the first three pages of results.
Job details are extracted from each listing.
The collected information is stored in a CSV file.
📄 Output

The final CSV file contains the scraped job listings with the following columns:

Job Title
Company Name
Job Location
Required Experience
Full Job Description

The scraped data will be saved as a CSV file.
