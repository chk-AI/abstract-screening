# abstract-screening
Python script for conducting systematic literature reviews through automated PubMed searches based on defined PICO criteria, analyzing titles and abstracts with different large language models for abstract inclusion

## Project description
This project automates the process of conducting title and abstractscreening in systematic literature reviews by utilizing a Python script to search PubMed based on defined PICO (Population, Intervention, Comparison, Outcome) criteria. It extracts relevant information, analyzes the search results with six different large language models, and saves results as CSV.

## Features
- **Automated PubMed Searches:** Search based on customizable PICO criteria.
- **Data Extraction:** Automatically extracts necessary data from search results, such as DOI, authors, title, and abstract.
- **Analysis with LLMs:** Uses six different large language models to evaluate and select the best abstracts for the review.

## Prerequisites
- Python (current code is written in Google Colab and does not require installation of Python)
- API keys for OpenAI and Claude (available from: https://openai.com/index/openai-api/ and https://www.anthropic.com/api).
