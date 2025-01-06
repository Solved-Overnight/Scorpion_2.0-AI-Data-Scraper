# Scorpion 2.0: AI Data Scraper

A Streamlit-based web scraping application designed to simplify the process of extracting data from web pages. it streamlines data collection and visualization, making it ideal for showcasing extracted web data in a modern and professional manner.

![Preview Image](https://raw.githubusercontent.com/RSB-bd/Trending_doodle/refs/heads/main/Scorpion%20The%20Data%20Scraper.webp)

## Features

- Easy-to-use web interface.
- Custom field specification for data extraction.
- Pagination
- Dynamic data processing with Python and Streamlit.
- Direct download capabilities for extracted data in various formats.
- Attended mode

## Prerequisites

Before you begin, ensure you have the following installed:
- Python 3.6 or higher
- Pip for managing Python packages

## Installation

Follow these steps to get your development environment running:

```bash
# Clone the repository
git clone https://github.com/reda-marzouk608/scrape-master
cd scrape-master

# It's recommended to create a virtual environment
python -m venv venv
# Activate the virtual environment
# On Windows
venv\Scripts\activate
# On MacOS/Linux
source venv/bin/activate

# Install the required packages
pip install -r requirements.txt
```

## Launching the Application

To run ScrapeMaster, navigate to the project directory and run the following command:

```bash
streamlit run streamlit_app.py
```


## Usage
After launching the application, open your web browser to the indicated address (typically http://localhost:8501). Use the sidebar to input the URL and fields you wish to scrape, then click the "Scrape" button to see results.
