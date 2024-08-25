# Apartment Finder

## Overview

Apartment Finder is a Python script that scrapes apartment listings from [Blueground](https://www.theblueground.com/furnished-apartments-dubai-uae), filters them based on a specified maximum price, and sends an email with the filtered listings. This tool is designed for users looking for apartments within a budget and prefer automated email notifications.

## Features

- **Web Scraping:** Retrieves apartment listings from Blueground.
- **Price Filtering:** Filters apartments based on a user-defined maximum price.
- **Email Notifications:** Sends an email with the filtered apartment listings.
- **Scheduling:** Automatically runs the script daily using APScheduler.

## Technologies Used

- **Python:** The primary language for scripting and automation.
- **BeautifulSoup:** For parsing HTML and extracting apartment data.
- **Requests:** For sending HTTP requests to the Blueground website.
- **Smtplib:** For sending emails.
- **APScheduler:** For scheduling the script to run daily.
