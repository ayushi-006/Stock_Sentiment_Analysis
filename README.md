# Stock_Sentiment_Analysis

## Project Overview

This project performs sentiment analysis on stock-related discussions from Reddit to gauge market sentiment for various stocks. It uses Natural Language Processing techniques to analyze the sentiment of Reddit posts and comments.

## Features

- Data extraction from Reddit (implemented in `scraping.ipynb`)
- Text preprocessing and cleaning
- Sentiment analysis on extracted text
- Visualization of sentiment results

## Prerequisites

Before running this project, ensure you have:
- Python 3.x installed
- pip (Python package installer)

## Installation

1. Clone the repository:
```
git clone https://github.com/ayushi-006/Stock_Sentiment_Analysis.git
cd Stock_Sentiment_Analysis
```

2. Install required dependencies:
```
pip install -r requirements.txt
```

## Project Structure

```
Stock_Sentiment_Analysis/
├── scraping.ipynb          # Jupyter notebook for Reddit data extraction
├── sentiment_analysis.py   # Main script for performing sentiment analysis
├── requirements.txt        # List of Python dependencies
└── README.md              
```

## Data Collection

The project includes a Jupyter notebook (`scraping.ipynb`) that handles the extraction of text data from Reddit. This notebook:
- Connects to the Reddit API
- Scrapes posts and comments from relevant subreddits
- Preprocesses and saves the collected data

## Running the Code

1. First, run the data collection notebook:
```
jupyter notebook scraping.ipynb
```
Execute all cells to scrape and save Reddit data.

2. Run the sentiment analysis script:
```
python sentiment_analysis.py
```

## Dependencies

Key dependencies include:
- praw (for Reddit API interaction)
- pandas (for data manipulation)
- nltk (for text processing)
- textblob (for sentiment analysis)
- matplotlib and seaborn (for visualization)

All required packages are listed in `requirements.txt`

## Reddit API Setup

To use the Reddit scraping functionality:
1. Create a Reddit account
2. Go to https://www.reddit.com/prefs/apps
3. Create a new app to get your API credentials
4. Update the configuration in the scraping notebook with your credentials

## Contributing

Contributions are welcome! Feel free to open issues or submit pull requests.

## License

This project is open source and available under the [MIT License](LICENSE).
