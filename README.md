# Customer Sentiment Analysis from Airline Reviews

Analyzing Customer Sentiment from Reviews Published for 5 Different Airlines." This repository contains scripts and resources used in the project, including Python scripts for NLP analysis and web scraping automation, as well as a PowerPoint presentation of the Power BI report.

## Project Overview

In this project, we collected customer reviews from Skytrax for analysis of sentiment towards five different airlines. The goal was to gain insights into customer perceptions and preferences, enabling airlines to enhance their services and customer experiences.

## Repository Structure

- **`python_nlp_script.ipynb`**: Python script for preprocessing text data, applying NLP techniques, and generating sentiment analysis from customer reviews.
  
- **`web_scrape_automation.ipynb`**: Python script deployed on IBM Cloud for daily web scraping of new reviews from Skytrax.

- **`PowerBI_report.pptx`**: PowerPoint presentation containing visualizations and insights derived from the analyzed data using Power BI.

## Usage

### Python NLP Script

1. Ensure you have the necessary libraries installed (`pandas`, `nltk`, `vaderSentiment`, etc.).
2. Run `python_nlp_script.ipynb` to preprocess and analyze the customer review data.
3. The script will generate sentiment scores and insights based on the input data.

### Web Scraping Automation (IBM Cloud)

1. Set up an IBM Cloud account and create a Python runtime environment.
2. Deploy `web_scrape_automation.ipynb` as a scheduled task to run daily for retrieving new reviews from Skytrax.
3. Configure the script to store the scraped data in your preferred database or storage solution.

## Power BI Report

The PowerPoint presentation (`PowerBI_report.pptx`) provides an overview of the data analysis and visualizations created using Power BI. Review the slides to understand the key findings and insights derived from the analyzed customer sentiment data.
