# Consumer Behavior & Sentiment Analysis (Ulta Beauty)

This project analyzes over **300,000 Ulta Beauty product reviews** to explore customer behavior, product performance, and brand sentiment. The analysis combines EDA, clustering, and BERT-based sentiment modeling to better understand what drives positive and negative makeup experiences.

---

## Features
- Created **4 product segments** using K-Means, Hierarchical Clustering, and K-Medoids
- Applied a **BERT sentiment model** to classify review text (1–5 scale)
- Explored trends in price, review volume, rating patterns, and shade variety
- Compared sentiment across products and brands to identify strengths and recurring issues

---

## Tech Stack
- **Languages:** Python  
- **Libraries:** pandas, NumPy, scikit-learn, Matplotlib, Seaborn  
- **NLP:** BERT (nlptown/bert-base-multilingual-uncased-sentiment)

---

## Key Insights
- The beauty market forms **four consistent product clusters** with different engagement and pricing profiles
- Positive reviews often focus on *smoothness, blendability, and natural finish*
- Negative reviews tend to highlight *dryness, patchiness, oxidation, and shade mismatch*
- Brand sentiment strongly reflects consistency in formulation and user experience

---
## Project Structure
project/
├── data/
├── notebooks/
├── src/
├── figures/
├── reports/
└── requirements.txt

