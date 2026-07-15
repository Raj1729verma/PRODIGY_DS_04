# Task-04: Twitter Sentiment Analysis 📊

Analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes toward specific topics or brands.

This project was completed as part of the **Prodigy InfoTech Data Science Internship**.

---

## 📌 Overview

Social media platforms generate massive volumes of unstructured text data reflecting public opinion in real time. This project applies natural language processing (NLP) techniques to classify tweets by sentiment (Positive, Negative, Neutral, Irrelevant) and visualize how sentiment varies across different topics/entities.

## 🎯 Objectives

- Clean and preprocess raw tweet text (remove URLs, mentions, hashtags, punctuation, stopwords)
- Perform sentiment classification using lexicon-based and/or ML approaches
- Explore sentiment distribution across different entities/brands
- Visualize patterns using bar charts, pie charts, and word clouds

## 📂 Dataset

Sample dataset provided by Prodigy InfoTech:
[data-science-datasets/Task 4](https://github.com/Prodigy-InfoTech/data-science-datasets/tree/main/Task%204)

The dataset (Twitter Entity Sentiment Analysis) includes:

| Column | Description |
|---|---|
| Tweet ID | Unique identifier for each tweet |
| Entity | Topic/brand the tweet refers to |
| Sentiment | Label — Positive / Negative / Neutral / Irrelevant |
| Tweet Content | Raw text of the tweet |

Files: `twitter_training.csv`, `twitter_validation.csv`

## 🛠️ Tech Stack

- **Python 3**
- `pandas`, `numpy` – data manipulation
- `matplotlib`, `seaborn` – visualization
- `nltk` / `TextBlob` / `VADER` – sentiment scoring
- `wordcloud` – text visualization
- Jupyter Notebook

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn nltk textblob wordcloud
```

### Clone the repository
```bash
git clone https://github.com/<your-username>/<your-repo-name>.git
cd <your-repo-name>
```

### Run the notebook
```bash
jupyter notebook Task4_Sentiment_Analysis.ipynb
```

## 📈 Workflow

1. **Data Loading** — Import training/validation CSVs
2. **Data Cleaning** — Lowercase text, strip URLs/mentions/special characters, remove stopwords
3. **Sentiment Analysis** — Score each tweet using a lexicon-based tool (VADER/TextBlob) or a trained classifier
4. **Exploratory Analysis** — Aggregate sentiment counts by entity
5. **Visualization**
   - Overall sentiment distribution (bar/pie chart)
   - Sentiment breakdown per entity/brand
   - Word clouds for positive vs. negative tweets

## 📊 Sample Results

*(Add your generated charts here once the notebook is run, e.g.)*
```
![Sentiment Distribution](images/sentiment_distribution.png)
![Word Cloud](images/wordcloud_positive.png)
```

## 🔑 Key Insights

- Distribution of sentiment across the overall dataset
- Which entities/brands receive the most positive or negative attention
- Common themes/words associated with each sentiment class

## 📁 Repository Structure

```
├── Task4_Sentiment_Analysis.ipynb   # Main analysis notebook
├── data/
│   ├── twitter_training.csv
│   └── twitter_validation.csv
├── images/                          # Saved visualizations
├── README.md
└── requirements.txt
```

## 🙌 Acknowledgements

- Dataset & task provided by [Prodigy InfoTech](https://github.com/Prodigy-InfoTech/data-science-datasets)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---
⭐ If you found this useful, consider giving the repo a star!
