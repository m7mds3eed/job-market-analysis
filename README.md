Job Market Analysis and Scraping Project
This repository contains two main components: a Jupyter notebook for analyzing job market trends (Final Code.ipynb) and another for scraping job descriptions from a specific website (scrape_job_descriptions.ipynb).

Installation
First, clone the repository:

bash
Copy code
git clone https://git.cs.bham.ac.uk/projects-2023-24/msa183.git
cd msa183
Then, install the required dependencies:

bash
Copy code
pip install -r requirements.txt
Usage
Job Market Analysis Dashboard
Launch the analysis notebook to explore market trends and job postings:

bash
Copy code
jupyter notebook "Final Code.ipynb"
Interact with the notebook to access various analyses and insights on market trends and job postings.

Job Descriptions Web Scraper
This notebook (scrape_job_descriptions.ipynb) is designed to scrape job descriptions from Data Science Jobs, specifically targeting data science-related job postings.

Features
Scrapes job titles and descriptions from the specified website.
Processes and cleans the scraped data for further analysis.
Outputs the scraped data to a CSV file named job_descriptions.csv.
Running the Scraper
The scraper, when executed, will generate a file named job_descriptions.csv containing the scraped job titles and descriptions. This file is already included in the repository with pre-scraped data.

bash
Copy code
jupyter notebook "scrape_job_descriptions.ipynb"
Execute the cells within the notebook to start the scraping process. While the job_descriptions.csv file already exists with pre-scraped data, you can rerun the scraper to fetch more recent or updated data. This can be particularly useful if you need the most current data available for your analysis or if you want to track changes in the job market over time.

Output File
After running the scraper, you'll find job_descriptions.csv in the same directory as your notebook. If you run the scraper again, this file will be overwritten with the new data, so ensure you've backed up the previous version if needed.
