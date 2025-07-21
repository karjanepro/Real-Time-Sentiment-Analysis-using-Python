# 💬 Real-Time Sentiment Analysis using Python

This project demonstrates a **real-time sentiment analysis pipeline** built using Python. It captures live text input (such as tweets or user messages), processes it through natural language processing (NLP) pipelines, and classifies the sentiment as **positive**, **negative**, or **neutral**.

---

## 📌 Project Overview

Sentiment analysis is a key component of opinion mining, widely used in brand monitoring, customer feedback, and social media analysis. This project provides a simple yet effective implementation of real-time sentiment classification using Python.

---

## 🚀 Features

- Real-time text input support (simulated stream)
- Text preprocessing: tokenization, stopword removal, stemming
- Sentiment classification using:
  - **TextBlob**
  - **VADER (Valence Aware Dictionary)**
- Dynamic visualization of sentiment distribution
- Interactive console for testing and feedback

---

## 🧠 How It Works

### 1. **Input Pipeline**

- User can input text manually or simulate real-time data streams.
- The input is processed and analyzed as it arrives.

### 2. **Text Preprocessing**

- Removal of punctuation, stopwords
- Lowercasing
- Optional lemmatization or stemming

### 3. **Sentiment Detection**

The notebook implements and compares two models:

#### 🔹 **TextBlob**
- Rule-based classifier
- Outputs polarity (−1 to +1) and subjectivity

#### 🔹 **VADER**
- Lexicon and rule-based sentiment analysis specifically tuned for social media
- Outputs compound score and categorical sentiment

### 4. **Results Visualization**

- Sentiment distribution pie chart or bar graph
- Display of classified sentences with sentiment tags

---

## 🛠️ Tools & Libraries Used

- `TextBlob`
- `NLTK`
- `VADER SentimentIntensityAnalyzer`
- `Matplotlib` / `Seaborn` – for visualization
- `Pandas` – data handling
- `IPython.display` – for interactive outputs in Jupyter

---

## 📈 Sample Output

```text
Input: "I love this product! It's amazing 😍"
Output: Positive (TextBlob: 0.85, VADER: 0.93)

Input: "This is the worst experience I've ever had."
Output: Negative (TextBlob: -0.75, VADER: -0.84)
```
---
## 🧪 Use Cases
- Brand reputation monitoring
- Product review analysis
- Social media feedback classification
- Customer support sentiment routing

