# Documentations Scraper

## Overview
The Documentations Scraper is a tool designed to automate the process of extracting text and hyperlinks from web pages. It utilizes Selenium for loading the HTML source code of the target web page and BeautifulSoup for parsing the page content into a structured string/text format. This data can then be utilized for various purposes, including the generation of fine-tuning datasets for Large Language Models (LLMs).

## Purpose
This notebook demonstrates the process of scraping web documentation. It begins with loading the web page using Selenium to ensure dynamic content is rendered. Subsequently, BeautifulSoup is employed to parse the HTML source into a structured format. This structured data includes text content along with hyperlinks, which are particularly useful for creating comprehensive datasets for LLM fine-tuning.

## Environment Requirements
To set up your environment for running this scraper, you will need to install the following Python packages:

```shell
pip install beautifulsoup4
pip install selenium
```

## Author
- **Krittaprot Tangkittikun**
