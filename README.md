# AI-Web-Scraper
An AI-powered web scraper that automates data extraction, handles captchas, and fetches required information from a webpage. This project integrates Ollama for AI-driven data insights, Selenium for web automation, BeautifulSoup for HTML parsing, and BrightData for handling web scraping challenges like captchas.

## Features

- Automated Data Extraction: Scrapes web data dynamically using Selenium and BeautifulSoup.
- Captcha Handling: Integrates BrightData to bypass or solve captchas during scraping.
- AI-Powered Insights: Uses Ollama for advanced data analysis and extraction.
- Proxy Support: Secure and scalable scraping using proxies from BrightData.
- Multi-site scraping: Adaptable to scrape data from multiple web sources with custom selectors.

## Tech Stack

- Ollama: Integrate LLM for optimized data retrieval.
- Selenium: Automates web browser interactions.
- BeautifulSoup: Extracts and parses HTML content.
- BrightData: Bypasses captchas and provides proxy support.
- Python: Primary programming language.

## Prerequisites

1. Python 3.x installed.
2. Install the required Python libraries using:
```bash
   pip install -r requirements.txt
```
3. Selenium WebDriver for the browser you plan to use (e.g., ChromeDriver for Chrome).
4. BrightData Account for handling captchas and proxies.
5. Install ollama in your system.

## Setup

1. Clone the repository:
```bash
   git clone https://github.com/Kaushalvadadoria28/AI-Web-Scraper.git
```
2. Create and activate a virtual environment (optional but recommended):
```bash
   python -m venv venv
   venv\Scripts\activate
```
3. Install dependencies:
```bash
   pip install -r requirements.txt
```
4. Download and set up Selenium WebDriver for your browser (e.g., Chrome, Firefox).

## Usage

1. Run the scraper:
```bash
   streamlit run main.py
```
2. Once the app is running, you can enter the url of website for scraping and also you can interact with the content of website by typing natural language queries into the chat interface. The app will process your input and retrieve relevant data from the website.

## Handling Captchas

The project uses BrightData to bypass captchas. Ensure your BrightData proxy settings are correctly configured in the script. The scraper will automatically detect and solve captchas when they appear during the scraping process.

## Contributions

Feel free to open a pull request or submit an issue for bugs, feature requests, or improvements.
