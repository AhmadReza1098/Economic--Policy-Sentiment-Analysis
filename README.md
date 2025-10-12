# EcoPolicySentimentAnalysis

## Project Overview
This project performs sentiment analysis on economic policy-related news articles from the Economic Times focusing on the Reserve Bank of India (RBI) policies and related market reactions. The aim is to extract insights on how policy announcements influence market sentiment and investor behavior.

## Methodology
- Web scraping was used to collect news article titles, summaries, and full texts on RBI policies.
- Text data was cleaned and preprocessed using natural language processing techniques such as stopword removal and tokenization.
- Sentiment analysis was conducted using VADER (Valence Aware Dictionary and sEntiment Reasoner) to classify articles as positive, negative, or neutral.
- Visualization techniques including sentiment distribution histograms and word clouds for positive/negative summaries help to understand sentiment trends.

## Key Outputs and Insights
- Successfully scraped and processed 200+ RBI policy-related articles.
- Sentiment classification results showed a majority of articles reflected positive sentiment supporting market confidence.
- Compound sentiment scores ranged widely, with the most positive article scoring 0.966 and the most negative article scoring -0.897.
- Word clouds highlighted key terms associated with positive and negative sentiments in the RBI policy context.
- The analysis suggests gradual market optimism amid RBI maintaining or adjusting repo rates in response to economic conditions.

## Technologies Used
- Python libraries: Requests, BeautifulSoup, Pandas, NLTK (VADER), Matplotlib, WordCloud
- Data extraction, processing, sentiment scoring, and visualization workflows were implemented end-to-end.

## Conclusion
This project demonstrates effective application of NLP and sentiment analysis tools on economic policy data to reveal actionable market sentiment trends. Such insights can assist economists, financial analysts, and policymakers in understanding market reactions to monetary policy developments.
