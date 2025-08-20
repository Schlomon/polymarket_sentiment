# Do sentiments in news articles concering "Russia x Ukraine ceasefire in 2025?" relate to short-term price moves on Polymarket?

## Overview
This project analyzes whether the sentiment of news headlines about a potential Russia-Ukraine ceasefire in 2025 is related to short-term price movements on the Polymarket prediction platform. It collects news headlines, assigns sentiment scores, and compares them to market price changes over various time lags.

## Methodology
- **Data Collection:** News headlines mentioning "Russia", "Ukraine", and "ceasefire" were gathered from multiple sources using [GNews](https://gnews.io/).
- **Sentiment Analysis:** Headlines were scored using [GPT-4o mini](https://platform.openai.com/docs/models/gpt-4o-mini)
- **Market Data:** [Polymarket](https://polymarket.com/event/russia-x-ukraine-ceasefire-in-2025) price data for the relevant contract was retrieved at hourly intervals.
- **Correlation Analysis:** Sentiment scores and price changes were compared across different time lags to identify potential relationships.

# Results
The analysis found only weak correlations between headline sentiment and Polymarket price changes. Correlation coefficients ranged between about −0.15 and +0.17 across ±24-hour lags. Small positive peaks appeared around +5 to +10 hours, suggesting sentiment occasionally precedes price moves, while negative dips around −15 to −20 hours suggest price shifts can lead sentiment. Overall, the relationship is noisy and does not provide clear predictive power.