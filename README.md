# Automated Amazon Price Tracker & Alert System

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

An automated Python script that scrapes a product's price from Amazon, logs it over time, and sends you an email alert when the price drops below your target.

## Overview

As a passionate photographer, I wanted to buy a specific camera to take my hobby to the next level. However, I wanted to make sure I got the best deal possible. Instead of manually checking the Amazon page every day, I decided to build this tool to do the work for me.

This project is a simple yet powerful web scraper that automates the process of price tracking. It's a practical demonstration of web scraping, data logging, and task automation to solve a real-world problem.

## Key Features

- **Daily Price Scraping:** Automatically fetches the latest price of your desired product every 24 hours.
- **Historical Data Logging:** Saves the product title, price, and date into a CSV file to track price trends over time.
- **Automated Email Alerts:** Sends an email notification directly to your inbox when the price drops below a specified threshold.
- **Customizable:** Easily configurable to track any product on Amazon and set any price target.

## Technologies Used

- **Language:** `Python 3`
- **Libraries:**
    - `requests`: For making HTTP requests to the Amazon product page.
    - `BeautifulSoup4`: For parsing the HTML content and extracting data.
    - `pandas`: For handling and displaying the data from the CSV file.
    - `smtplib`: For sending the email notifications via a Gmail account.

## Getting Started

Follow these instructions to get a copy of the project up and running on your local machine.

### Prerequisites

Make sure you have Python 3 installed on your system.
```bash
python --version
