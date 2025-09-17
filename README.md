# Web-scraper-Project-LLMEngineering
My first web scraping tool using Python and OpenAI

This project fetches the content of any webpage, cleans it using BeautifulSoup, 
and then uses OpenAI's GPT-4o to generate a short summary.

## Features
- Web scraping with requests + BeautifulSoup
- Class-based design (`Website`)
- Prompt engineering with system + user messages
- Integration with OpenAI API

## How to run
1. Clone this repo
2. Create a `.env` file with your `OPENAI_API_KEY`
3. Install dependencies:
   pip install -r requirements.txt
4. Open the notebook in Jupyter and run cells top to bottom.

✅ requirements.txt
A plain text file listing libraries you used:
- requests
- beautifulsoup4
- python-dotenv
- openai
