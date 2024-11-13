![BullAndBearAI](https://github.com/user-attachments/assets/b89ce239-303f-41f8-aaff-867bbe978a50)
# **Autonomous BTC Sentiment AI**

A simple, experimental AI that autonomously tweets sentiment on Bitcoin (BTC) based on 4-hour candlestick data.

# **🚀 Overview**
This AI-powered bot analyzes BTC's 4-hour candle data and tweets a sentiment update. It identifies bullish or bearish sentiment based on recent price movements, providing real-time, data-driven insights. Currently in the experimental phase, this project is under active development as a test for potential future functionality.

# ⚙️ Features
🧠 Automated Sentiment Analysis: Leverages 4-hour BTC candlestick data to gauge positive or negative sentiment.

🐦 Autonomous Twitter Posting: Posts tweets reflecting the latest BTC market sentiment in real-time.

📈 Configurable Thresholds: Define custom sentiment thresholds for bullish or bearish tweets.

🔄 Continuous Monitoring: Analyzes BTC data on a recurring 4-hour basis for consistent, up-to-date feedback.

🛠️ Getting Started

Prerequisites
Python: Version 3.7+ is required.
Twitter API Access: You’ll need API keys from Twitter to post updates from the bot.
Environment Setup
Clone this repository:

git clone https://github.com/your-repo/btc-sentiment-ai.git
cd btc-sentiment-ai
Install required dependencies:

pip install -r requirements.txt
Set up the environment variables:

Copy .env.example to .env and fill in with your Twitter API credentials and any other relevant settings.
Running the Bot
To start the bot, use the following command:

python main.py
The bot will begin monitoring BTC’s 4-hour candlestick data and post tweets based on the sentiment thresholds defined in the configuration.

⚙️ Configuration
Edit the config.yaml file to adjust sentiment thresholds, tweet frequency, and other settings:

yaml
Code kopieren
# Sample configuration
SENTIMENT_THRESHOLD_POSITIVE: 2.0
SENTIMENT_THRESHOLD_NEGATIVE: -2.0
TWEET_INTERVAL_HOURS: 4
📌 Current Limitations
Experimental Project: This is a new and evolving test project, currently in a proof-of-concept stage.
Market Sentiment Only: The bot uses simple metrics based on BTC's 4-hour candlestick data and does not consider other market factors.
📄 Future Plans
This project aims to explore various improvements, including:

Incorporating advanced machine learning models for deeper sentiment analysis.
Extending support to additional cryptocurrencies and timeframes.
Enabling multi-platform posting to expand reach.
🤝 Contributions
As this is an experimental project, contributions are welcome! Please open an issue or submit a pull request with improvements or feedback.
