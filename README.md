# **Apartment Finder Bot**

## **Overview**

The Apartment Finder Bot is a Python application designed to automate the process of finding apartments. Using web scraping techniques, this bot navigates rental websites to extract information about available apartments, helping users find the best deals quickly and efficiently. This project demonstrates how to use Python for web scraping, handling common challenges, and integrating proxy services to bypass restrictions.

## **Features**

- **Web Scraping**: Automatically extracts apartment listings from rental websites.
- **Dynamic Search**: Allows users to specify the city and other search criteria.
- **Proxy Integration**: Uses DataImpulse proxies to handle website restrictions and IP bans.
- **Beginner-Friendly**: Step-by-step tutorial and code examples provided.

## Getting Started

To use this bot, you'll need to set up your environment and install the required libraries.

### Prerequisites

- Python 3.x
- `requests` library
- `beautifulsoup4` library
- DataImpulse account (for proxies)

### Installation

1. Clone this repository:

   ```bash
   git clone https://github.com/gamzeozgul/apartment-finder.git
   cd apartment-finder

2. Install the required Python packages:

   ```bash

    pip install requests beautifulsoup4


3. Create a DataImpulse account to obtain proxy details:

  -Go to DataImpulse.

  -Sign up and create a plan.

  -Retrieve your proxy credentials from the dashboard.

### Configuration

1. Update the config.py file with your DataImpulse proxy details:

   ```bash

    PROXY_HOST = 'your_proxy_host'
    PROXY_PORT = 'your_proxy_port'
    PROXY_USER = 'your_proxy_user'
    PROXY_PASS = 'your_proxy_pass'

2. Modify the url variable in main.py to specify the rental website URL you want to scrape.

### Usage

1. Run the bot:

   ```bash
    python main.py

2.The bot will start scraping the specified website and output the results.

### How It Works

1. **Web Scraping:** The bot sends a request to the rental website and retrieves the HTML content.

2. **Parsing HTML:** Using BeautifulSoup, the bot parses the HTML and extracts relevant information about apartments.

3. **Handling Restrictions:** DataImpulse proxies are used to bypass any IP bans or restrictions set by the website.

### Common Issues

  - **Blocked IP Addresses:** Use proxies to avoid being blocked by the website.

  - **CAPTCHAs:** DataImpulse proxies can help bypass CAPTCHAs and other anti-bot measures.
    
  - **Website Changes:** If the website layout changes, you may need to update the scraping logic.
