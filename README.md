# Google News Scraper

This Python project is a versatile Google News scraper that allows users to collect and organize news articles based on specific search terms. It utilizes the GNews API and the Newspaper library to retrieve news links, extract article content, and compile the data into a structured format. The scraper captures essential information such as publication dates, sources, article titles, and full article text. The extracted data is then saved to a CSV file for further analysis and insights.

## Features

- Supports custom search terms to monitor trending topics or specific keywords.
- Retrieves news links and downloads article content for comprehensive data.
- Organizes data into a CSV file for easy access and analysis.

## Getting Started

To get started with the Google News Scraper, follow these steps:

1. Clone this repository to your local machine.
2. Install the required Python libraries using `pip install -r requirements.txt`.
3. Customize the `trends_names` list in the `main` function with your desired search terms.
4. Run the `extract_news` function to start scraping news articles.

## Usage

```python
# Example usage
trends_names = ["qatar", "fifa", "football"]
for search_term in trends_names:
    extract_news(search_term)
