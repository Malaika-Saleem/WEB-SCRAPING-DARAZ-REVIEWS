This Python script utilizes Selenium to scrape and analyze product reviews from a specific Daraz.pk product. The code extracts reviewer names, review text, and performs sentiment analysis using the NLTK library.

Script Overview
Setting Up WebDriver: The script initializes Chrome WebDriver using the webdriver module from Selenium and navigates to the provided Daraz.pk product URL.

Data Extraction: Reviewer names and review text are extracted from the product reviews section by scrolling down the page and navigating through review pages.

Saving to CSV: Extracted data is organized into a Pandas DataFrame and saved to a CSV file.

Sentiment Analysis: NLTK's SentimentIntensityAnalyzer is employed to analyze the sentiment of each review. Sentiment scores (compound) are appended to the DataFrame.
