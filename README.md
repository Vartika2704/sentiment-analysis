🗳️ Election Sentiment Analysis Using Twitter Data
This project performs sentiment analysis on Indian election-related tweets using both BERT-based multilingual sentiment classification and the VADER sentiment analyzer. The focus is on analyzing public sentiment for political figures such as Narendra Modi and Rahul Gandhi based on tweets from the 2019 Indian General Election.

📌 Objective
To mine, filter, and analyze sentiment trends from Twitter data related to key political leaders, leveraging natural language processing and transformer-based models.

🧰 Features
🔍 Filters tweets using keywords and hashtags for politicians (e.g., #PMModi, #RahulGandhi)

🧠 Uses:

nlptown/bert-base-multilingual-uncased-sentiment for BERT-based sentiment scoring

VADER for rule-based sentiment polarity analysis (positive, negative, neutral)

📈 Plots and visualizes sentiment trends using Matplotlib, Seaborn, and Plotly

📂 Project Structure
plaintext
Copy
Edit
.
├── election.ipynb                  # Jupyter Notebook with analysis
├── IndianElection19TwitterData.csv # Input dataset of tweets
├── README.md                       # Project documentation
├── requirements.txt                # Required libraries
🚀 How to Run
1. ✅ Install Required Packages
bash
Copy
Edit
pip install -r requirements.txt
Includes:

transformers

torch

pandas

matplotlib

seaborn

plotly

vaderSentiment

2. 💻 Open the Notebook
bash
Copy
Edit
jupyter notebook election.ipynb
Run all cells sequentially to:

Load tweet dataset

Filter tweets for specific leaders

Compute sentiment scores

Visualize sentiment trends

🧠 Models Used
🔹 BERT (HuggingFace Transformers)
Model: nlptown/bert-base-multilingual-uncased-sentiment

Predicts sentiment on a scale of 1 (negative) to 5 (positive)

🔹 VADER (Valence Aware Dictionary and sEntiment Reasoner)
Calculates compound sentiment score and individual polarity scores (pos/neg/neu)

📊 Sample Visualizations
Sentiment distribution for each leader

Word cloud of frequent keywords

Comparison bar charts between leaders

📚 Data Source
Dataset: IndianElection19TwitterData.csv

Contains tweet text, user info, and timestamp for tweets from the 2019 Indian General Election period.

🔮 Possible Enhancements
Add stream-based sentiment tracking with live Twitter API (Tweepy/SNScrape)

Extend to other parties or regional leaders

Use LSTM or multilingual BERT variants like IndicBERT for local language tweets

🧑‍💻 Author
👩‍💻 Vartika Chaudhary

📌 Disclaimer
This project is for educational and research purposes only. Sentiment analysis on social media content is inherently noisy and should not be treated as definitive public opinion.

