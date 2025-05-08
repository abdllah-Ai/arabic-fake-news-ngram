# Arabic Fake News Analysis using N-Grams

This project performs text preprocessing and N-Gram analysis on Arabic news claims to identify the most frequent patterns in real vs. fake news.

## 🔍 Objective

To compare linguistic patterns between fake and real Arabic news using:
- Unigrams
- Bigrams
- Trigrams
- Word Clouds
- Frequency Bar Charts

## 📁 Dataset

- **Source**: `AraFacts.csv`
- **Columns Used**: `claim`, `normalized_label`
- **Labels Converted**: 
  - `True` → Real
  - `False`, `Partly-false` → Fake

## 🛠️ Features

- Arabic text normalization
- Stop word removal
- Tokenization
- N-gram extraction
- Visualization using matplotlib and wordcloud

## 📦 Requirements

Install the required packages using:

```bash
pip install -r requirements.txt
```

## ▶️ How to Run

Make sure `AraFacts.csv` is in the same directory, then:

```bash
python your_script_name.py
```

## 📊 Output

- Top 10 Unigrams, Bigrams, and Trigrams for each category (Fake, Real)
- Word Clouds per category
- Horizontal bar charts for frequency comparison

## 📌 Notes

- Make sure to download NLTK stopwords beforehand (done automatically in script).
- Font used for Arabic wordcloud rendering: `arial`
