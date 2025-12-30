# Reddit Web Data Scraping and Analysis

## Project Overview
This project looks at top posts from the subreddit r/AmItheAsshole. This subreddit was chosen because the posts are rich in content and engagement, making it suitable for analyzing post length, scores, comments, and members' interactions.

## Files
- reddit_data_analytics.ipynb - full jupyter notebook
- AmItheAsshole_reddit_data.json - json file
- scraped_reddit_data.csv - Data in csv format

## Key Steps
- Scraped data from reddit using
- Cleaned data (removed unecesary columns, cleaned text)
- Used word cloud to explore frequency of words
- Explored judgement of posts
- Data Collection/Scraping: The dataset was scraped programmatically from r/AMItheAsshole using the Reddit API.
- The loop was set to fetch 500 posts but only 247 was fetched.
- HTTP headers was used to prevent being blocked
- Data was then converted to pandas dataframe and then csv.

## How to run
- Make sure you have python 3 and the libraries installed (see libraries below)
- Open reddit_data_analytics.ipynb in jupyter Notebook or VS code and run cells orderly.

## Tools/Libraries Used
- Python
- Pandas
- Numpy
- Matplotlib
- Seaborn
- WordCloud

## The following questions were answered
- Does the length of an 'AMItheAsshole' post affect how much engagement (score and number of comments) it receives?
## Sub-questions
- Is there a linear relationship between the length of post and its score?
- Does the word count have a relationship with the number of comments a post receives?
- Are longer posts more common in certain flairs (judgements)?

## Main finding
From this analysis of top r/AmItheAsshole posts, some patterns were noticed. Over 90% of posts received the judgement Not the Asshole, suggesting that posts where the narrative is perceived positively are the most popular. The word cloud visualization reflected the theme of this subreddit with words showing narrations and interpersonal relationships as the most frequent. The average score (approximately 13,370) and number of comments (around 1776) further indicated that the scraped posts attracted high community engagement. Although, this was expected because the dataset contained only top posts. The data covers a time window between December 2024 and November 2025, and crossposts were rare.
