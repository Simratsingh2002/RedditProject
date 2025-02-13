# Reddit Text Content Scraper

This Python program scrapes HTML content from Reddit posts and their comments. The extracted data is saved to a text file for analysis. Additionally, sentiment analysis is performed on the comments, and results are visualized using Matplotlib.

## Features

This project includes the following features:

✅ Scrapes HTML content from Reddit posts and their comments.  
✅ Saves extracted data to a text file (`output.txt`).  
✅ Performs sentiment analysis on extracted comments.  
✅ Generates sentiment analysis plots using Matplotlib and Pandas.  
✅ Fully automated process once executed.  

## Technologies Used

The project utilizes the following technologies:

- **Python 3.7+** – Main programming language.  
- **Conda** – For managing dependencies.  
- **Pandas** – For data handling and sentiment analysis.  
- **Matplotlib** – For generating visual sentiment analysis plots.  

## Project Structure

The project is organized as follows:

📁 Reddit-Text-Scraper
│── 📁 Data (Contains output files and sentiment analysis results)
│── 📁 Plots (Generated visualizations from sentiment analysis)
│── 📁 scripts
│ ├── run.py (Main scraper script)
│ ├── plots.py (Generates sentiment analysis plots)
│ ├── config.py (Stores API credentials)
│── urls.txt (Contains Reddit post URLs)
│── requirements.yaml (Dependencies for Conda environment)
│── README.md (This file)

## Setup Instructions

To set up and run the project, follow these steps:

### 1️⃣ Clone the Repository
Download the project from GitHub:
git clone https://github.com/SimratSinghBhatia/Reddit-Text-Scraper.git
cd Reddit-Text-Scraper

### 2️⃣ Set Up the Environment
Create a Conda environment and install dependencies:
conda env create -f requirements.yaml
conda activate reddit-scraper

###3️⃣ Add API Credentials
Edit the config.py file and add your Reddit API credentials:
# In config.py  
REDDIT_CLIENT_ID = "your_client_id"  
REDDIT_CLIENT_SECRET = "your_client_secret"  
REDDIT_USERNAME = "your_username"  
REDDIT_PASSWORD = "your_password"  
api_key = "your_openai_api_key"  

## Running the Program
Execute the main script to scrape Reddit content:
python run.py

- The program reads URLs from urls.txt, scrapes Reddit content, and saves it to output.txt.
- Comment extraction and sentiment analysis are performed automatically.
  
To generate sentiment analysis plots, run:
python plots.py

## Future Improvements
✅ Enhance the scraper's efficiency for large datasets.
✅ Improve data visualization with interactive graphs.
✅ Add a web interface for running the scraper easily.

## Author
Simrat Singh Bhatia
