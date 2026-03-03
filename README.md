# NLP-SMS-Analysis

# 📱 NLP SMS Chat Analysis

A Natural Language Processing (NLP) project analyzing SMS chat data to uncover conversational themes and emotional patterns using topic modeling and sentiment analysis.

---

## 📌 Project Summary

This project applies modern NLP techniques to analyze thousands of SMS messages and extract meaningful conversational patterns.

Using text preprocessing, TF-IDF vectorization, Latent Dirichlet Allocation (LDA), and sentiment analysis, the project identifies dominant conversation themes and explores how emotional tone varies across them.

The analysis reveals that:
- Friendly and affectionate conversations are the most positive.
- Informal social interactions are strongly positive.
- Logistical and planning-related messages are predominantly neutral.
- Emotional tone varies significantly depending on communication intent.

This project demonstrates end-to-end NLP workflow implementation, from raw text preprocessing to interpretable topic–sentiment insights.

---

## 🎯 Objectives

- Clean and preprocess SMS text data
- Perform exploratory text analysis
- Identify common phrases and patterns (n-grams)
- Convert text into numerical features using TF-IDF
- Apply LDA topic modeling
- Assign dominant topics to each message
- Perform sentiment analysis using TextBlob
- Analyze sentiment distribution across topics
- Visualize key findings

---

## 🧠 NLP Techniques Used

The following NLP techniques were applied:

- **Regular Expressions (regex)** for text parsing and cleaning
- **Tokenization and stopword removal**
- **Bag-of-Words representation**
- **N-gram analysis (bigrams)**
- **TF-IDF vectorization**
- **Latent Dirichlet Allocation (LDA)**
- **Sentiment analysis (TextBlob polarity scoring)**
- **Topic–Sentiment interaction analysis**

---

## 🗂 Dataset Overview

- ~48,000 SMS messages
- Text-based conversational data
- Cleaned and normalized before analysis

---

## 🔎 Exploratory Text Analysis

Initial exploration included:

- Most frequent words
- Bigram frequency analysis
- Message length distribution
- Word frequency ranking

This provided early insights into conversational structure and informal language patterns.

---

## 🏷 Topic Modeling (LDA)

LDA was used to identify 5 dominant conversational themes:

1. Availability & Logistics  
2. Affection & Friendly Conversation  
3. Meetups & Transportation Planning  
4. General Informal Discussion  
5. Food & Casual Social Interaction  

Each message was assigned a **dominant topic**, enabling structured analysis.

---

## 😊 Sentiment Analysis

Sentiment polarity was calculated using TextBlob and categorized into:

- Positive
- Neutral
- Negative

Overall sentiment distribution shows:

- Predominantly neutral-to-positive tone
- Lower proportion of negative messages
- Social themes contributing most to positive sentiment

---

## 📊 Topic–Sentiment Insights

By combining topic modeling with sentiment analysis:

- **Affection & Friendly Conversation** is the most positive topic.
- **General Informal Discussion** is also strongly positive.
- **Availability & Logistics** is primarily neutral.
- Social themes (food, greetings, casual chat) increase positive tone.

This demonstrates how emotional tone varies across conversational intent.

---

## 📈 Visualization

The project includes visualization of:

- Sentiment distribution across topics
- Topics ranked by positive sentiment percentage

These visualizations improve interpretability and communication of findings.

---

## 🛠 Tech Stack

- Python 3.11
- pandas
- NumPy
- scikit-learn
- NLTK
- TextBlob
- Matplotlib
- Jupyter Notebook

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone <your-repo-url>
   cd NLP-SMS-Analytics

2. Create a virtual environment:
 ```bash
 python -m venv .venv
source .venv/bin/activate
```

3. Install dependencies:
``` bash
pip install -r requirements-freeze.txt
```

4. Run the notebook:
```bash
jupyter notebook
```

---

## 📌 Key Takeaways

- NLP can effectively uncover conversational structure in informal SMS data.

- Topic modeling provides interpretable themes without labeled data.

- Sentiment varies strongly depending on conversational context.

- Combining topic modeling with sentiment analysis creates richer insights than either technique alone.
