# 🔎 Data Engineer Jobs Scraper

## 📌 Project Overview

This project uses **Python and Selenium** to scrape real job listings for **Data Engineer** positions from the **Naukrigulf** job portal.

The scraper navigates through the first **three pages** of search results, extracts detailed information from each job listing, and saves the collected data into a structured **CSV file**.

## 🎯 Objectives

* Automate web browsing using **Selenium**
* Search for **Data Engineer** job listings
* Navigate through multiple pages dynamically
* Extract detailed job information
* Export the collected data to a CSV file

## 📊 Data Collected

For each job listing, the scraper extracts:

| Field                    | Description                          |
| ------------------------ | ------------------------------------ |
| **Job Title**            | Title of the position                |
| **Company Name**         | Hiring company                       |
| **Job Location**         | Location of the job                  |
| **Required Experience**  | Experience required for the position |
| **Full Job Description** | Complete description of the job      |

## 🛠️ Technologies Used

* 🐍 **Python**
* 🌐 **Selenium**
* 📄 **CSV**

## 📁 Project Structure

```text
Data-Engineer-Jobs-Scraper/
│
├── scraper.py
├── Data_Engineer_Jobs.csv
└── README.md
```

## ⚙️ How It Works

1. Selenium opens the Naukrigulf job portal.
2. The scraper searches for **Data Engineer** jobs.
3. It navigates through the first **three pages** of search results.
4. Job information is extracted from each listing.
5. The extracted data is stored in a CSV file.

## 🚀 How to Run

### 1. Clone the repository

```bash
git clone YOUR_REPOSITORY_URL
cd Data-Engineer-Jobs-Scraper
```

### 2. Install Selenium

```bash
pip install selenium
```

### 3. Run the scraper

```bash
python scraper.py
```

The scraped job listings will be saved to the CSV file.

## 📄 Output

The generated CSV file contains:

```text
Job Title
Company Name
Job Location
Required Experience
Full Job Description
```


The objective of this project is to use Selenium with Python to scrape **Data Engineer** job listings from the first three pages of Naukrigulf search results and export the extracted information to a structured CSV file.
