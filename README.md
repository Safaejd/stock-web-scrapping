# stock-web-scrapping

📊 Web Scraping & Stock Market Analysis Using Yahoo Finance

📚 Project Overview

This project extracts and analyzes stock data and related news articles from Yahoo Finance using web scraping techniques. The goal is to:

✅ Scrape stock data and related news articles across various sectors
✅ Analyze sentiment and classify articles as Positive, Neutral, or Negative using NLP techniques
✅ Visualize market trends, sentiment distribution, and sector-specific insights
📈 Sectors Analyzed

Technology: Key stocks like Apple, Microsoft, and NVIDIA were analyzed, revealing trends in AI and cloud computing with generally positive sentiment but notable negative perceptions of IBM and AVGO.
Real Estate: Analyzed major real estate stocks with a focus on financial performance and market sentiment, finding mildly positive sentiment and moderate objectivity in news articles.
Healthcare: Sentiment was split between pharma leaders (JNJ, LLY) with positive sentiment and healthcare services (TMO, UNH) with negative sentiment due to investor skepticism.
Consumer Cyclical: Analysis of stocks like Home Depot and Starbucks highlighted diverse sentiment patterns, reflecting strong earnings and labor challenges.
Mutual Funds: Evaluated YTD returns and sentiment trends, identifying top-performing funds with strong investor confidence and others with cautious market perceptions.
🛠️ Tools & Libraries Used

Web Scraping: BeautifulSoup, Selenium
Data Processing: Pandas, NumPy
Sentiment Analysis: VADER (Valence Aware Dictionary and sEntiment Reasoner)
Visualization: Matplotlib, Dash
📊 Key Insights

Sentiment Trends: Positive sentiment often aligns with strong investor confidence, while negative sentiment indicates regulatory concerns or operational challenges.
Sector-Specific Patterns: Real estate and technology sectors show moderate sentiment with low volatility, while healthcare and consumer cyclical stocks reveal higher sentiment fluctuations.
Challenges Overcome: Dynamic content loading, IP blocking, and inconsistent page structures required adjusting scraping techniques, rotating user-agents, and refining search terms to extract relevant data.
