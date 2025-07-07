# fashion-sentiment-analyzer
# 👗 Cross-Platform Fashion Brand Sentiment Analyzer

An end-to-end NLP project using **live Twitter and Reddit data** to analyze public sentiment on sustainable fashion brands like **Patagonia, Reformation, Everlane, Allbirds**, and **Stella McCartney**.

This project cross-validates consumer opinions across platforms and visualizes sentiment through charts and word clouds — useful for **brand analysts**, **social media teams**, or **ethical fashion researchers**.

---

## 📌 Project Objectives

- 📥 Collect live data from **Twitter** (via Tweepy) and **Reddit** (via PRAW)
- 🧼 Clean and preprocess text using regular expressions and string operations
- 💬 Perform **sentiment analysis** using VADER
- ☁️ Generate WordClouds for positive/negative tweets
- 📊 Visualize sentiment distribution
- 📈 Compare **brand-wise sentiment** across platforms

---

## 🛠️ Tools & Libraries

| Purpose               | Tool / Library         |
|------------------------|------------------------|
| Twitter API            | `tweepy`               |
| Reddit API             | `praw`                 |
| Data manipulation      | `pandas`, `numpy`      |
| Sentiment analysis     | `vaderSentiment`       |
| Visualization          | `matplotlib`, `seaborn`, `wordcloud` |
| Notebook environment   | Google Colab / Jupyter |

---

## 📁 Folder Structure
fashion-sentiment-analyzer/
│
├── data/
│   ├── fashion_sentiment_labeled.csv         # Cleaned & labeled Twitter data
│   └── reddit_fashion_sentiment.csv          # Cleaned Reddit data
│
├── notebooks/
│   ├── 01_twitter_data_collection.ipynb
│   ├── 02_twitter_sentiment_analysis.ipynb
│   ├── 03_reddit_data_collection.ipynb
│   ├── 04_combined_visualization.ipynb
│
├── visuals/
│   ├── twitter_sentiment_distribution.png
│   ├── reddit_sentiment_distribution.png
│   ├── wordcloud_positive.png
│   ├── wordcloud_negative.png
│   └── brand_comparison.png
│
├── requirements.txt
├── README.md
└── .gitignore

---

## 📊 Visual Insights

### 🌐 Twitter Sentiment Distribution

![Twitter Sentiment](visuals/twitter_sentiment_distribution.png)

---

### 👽 Reddit Sentiment Distribution

![Reddit Sentiment](visuals/reddit_sentiment_distribution.png)

---

### ☁️ WordClouds

| Positive | Negative |
|----------|----------|
| ![Positive](visuals/wordcloud_positive.png) | ![Negative](visuals/wordcloud_negative.png) |

---

### 📈 Brand Sentiment Comparison (Reddit vs Twitter)

![Brand Comparison](visuals/brand_comparison.png)

---

## 🔍 Brands Analyzed

- Patagonia  
- Reformation  
- Everlane  
- Allbirds  
- Stella McCartney  

---

## 🤝 Future Work

- 🌐 Add Instagram and TikTok data scraping
- 🧠 Use advanced NLP (e.g., BERT sentiment or LLM-based classification)
- 🧑‍💻 Deploy an interactive **Streamlit dashboard**
- 📅 Add time-series sentiment tracking

---

## 🧑‍💻 Author

Made with ❤️ by **Abiha Hameed**  
🎓 6th Semester — [Lahore Garrison University]  
📬 [Email: abihahameed5@gmail.com]

---

## ✅ Installation

Install dependencies:

```bash
pip install -r requirements.txt



