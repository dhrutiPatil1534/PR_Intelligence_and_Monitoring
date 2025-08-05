# PR_Intelligence_and_Monitoring
A powerful tool to track and analyze brand or influencer reputation using real-time web scraping and NLP. Gathers data from Reddit, Twitter, Instagram, news, and Wikipedia. Features daily auto-updates, sentiment analysis, crisis detection (via BERT), and structured CSV outputs per company/influencer.

🔍 **Brand Reputation Analyzer & Crisis Classification Engine**
This project aims to automate the monitoring and analysis of public sentiment, brand reputation, and PR events related to companies and influencers using real-time data scraped from multiple platforms.

**🌐 Feature 1: Brand Reputation Analyzer**
Objective: Extract and analyze social sentiment and public perception.
_•	Data Sources:_
    o	Wikipedia (Company Profile)
    o	Reddit (via PRAW)
    o	Twitter/X (via Tweepy or snscrape)
    o	Instagram (via Instaloader/Selenium)
    o	News sites (via BeautifulSoup, News APIs)
_•	Extracted Parameters:_
    o	Basic company info (name, HQ, website, CEO, market cap, etc.)
    o	Social sentiment, brand perception, pros/cons
    o	News headline trends, controversies, NPS proxy
    o	Social media engagement & follower data
•	_Output:_ .csv files updated daily, stored in structured folders under /output/{company_name}/
•	_UI:_ A clean input interface where users enter the company/influencer name and optional keywords.

🔥 **Feature 2: Crisis Classification Engine**
Objective: Detect if a PR crisis is real or fake using NLP.
•	_Tech Stack:_
    o	BERT / RoBERTa for text classification
    o	NER for entity detection
    o	Custom crisis classification pipeline

⏱ _Automation & Scheduling_
    •	Built-in scheduler (CRON) for daily scraping
    •	Smart keyword extraction for dynamic topic tracking
    •	Output auto-appends new entries, preserving historical data

🗂 _File Structure & Deployment_
    •	Modular Python scripts
    •	API configuration for Reddit, Twitter
    •	Structured .csv datasets per company
•	Easily deployable and scalable

