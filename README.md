# NLP Decision Support: Apple Customer Review Analysis

**University of Newcastle · Business Analytics · 2024**  
`Python` `NLP` `Sentiment Analysis` `Topic Modelling` `Data Visualisation` `Decision Support`

---

## 📌 Project Overview

Businesses receive thousands of customer reviews but rarely have the tools to analyse them at scale. This project addresses that gap by building a Python-based Natural Language Processing (NLP) pipeline that transforms unstructured Apple iPhone customer reviews into structured, actionable business insights for managerial decision-making.

Rather than reading reviews one by one, the pipeline automatically identifies customer sentiment patterns, recurring themes, and product concern areas — enabling faster, evidence-based decisions across product development, marketing, and customer experience.

---

## 🎯 Business Problem

Apple and similar consumer electronics companies collect large volumes of customer feedback but face challenges in:
- Identifying which product features are driving positive or negative sentiment
- Prioritising product improvement areas based on actual customer voice
- Tracking emerging quality or usability concerns at scale

This project demonstrates how NLP can be applied to address these challenges in a scalable, repeatable way.

---

## 📂 Repository Contents

| File | Description |
|---|---|
| `Python Code.ipynb` | Full NLP pipeline — data cleaning, EDA, sentiment analysis, topic modelling, visualisation |
| `Apple Product dataset.csv` | Raw dataset of 1,165 Apple iPhone customer reviews |
| `A Text Analytics Case Study on Apple Customer Reviews Report.pdf` | Full project report including methodology, findings, and business recommendations |

---

## 🔧 Methodology

### 1. Data Preparation
- Loaded 1,165 customer reviews; removed duplicates and missing values → **903 valid reviews retained**
- Applied text preprocessing: tokenisation, stop-word removal, lemmatisation, emoji removal, and text normalisation

### 2. Exploratory Data Analysis (EDA)
- Analysed rating distributions and sentiment trends across the dataset
- Identified patterns in review length, rating frequency, and sentiment polarity

### 3. Sentiment Analysis
- Classified reviews into **positive** and **negative** categories based on customer rating scores
- Visualised sentiment distribution and identified key drivers of each sentiment class

### 4. Topic Modelling (LDA)
- Applied **Latent Dirichlet Allocation (LDA)** to identify **10 recurring customer themes**
- Key themes identified: battery performance, camera quality, usability, product condition, value for money, customer service, software performance, durability, delivery/packaging, and accessories

### 5. Visualisation
- Generated **word clouds**, frequency plots, bigrams, and trigrams to highlight commonly discussed product features
- Produced charts showing topic distribution and sentiment patterns across the dataset

---

## 📊 Key Findings & Business Value

| Theme | Insight | Business Action |
|---|---|---|
| Battery performance | Most frequently cited concern in negative reviews | Prioritise battery improvement in next product cycle |
| Camera quality | Top driver of positive sentiment | Leverage in marketing communications |
| Value for money | Mixed sentiment — price sensitivity evident | Inform pricing and bundle strategy |
| Product condition | Significant complaints about packaging/delivery | Review supply chain and packaging standards |
| Customer service | Recurring negative theme | Flag to customer experience team |

> **Outcome:** This pipeline demonstrates how NLP can reduce manual review analysis effort significantly and provide product, marketing, and service teams with a structured, evidence-based view of the customer voice — supporting faster and more confident business decisions.

---

## 🛠️ Tools & Libraries

| Category | Tools |
|---|---|
| Language | Python 3 |
| Data Processing | Pandas, NumPy |
| NLP | NLTK, Gensim |
| Machine Learning | Scikit-learn (LDA) |
| Visualisation | Matplotlib, Seaborn, WordCloud |
| Environment | Jupyter Notebook |

---

## ⚖️ Ethical Considerations

This project acknowledges the importance of responsible AI use in business contexts:
- **Data privacy:** Analysis is based on publicly available review data; no personally identifiable information was used
- **Bias awareness:** Sentiment models trained on rating-based labels may reflect rating bias rather than true sentiment
- **Responsible use:** NLP insights should inform, not replace, human judgement in business decisions

---

## 📄 Full Report

A complete project report covering methodology, detailed findings, visualisations, and stakeholder recommendations is available in the repository:  
📎 [View Full Report (PDF)](./A%20Text%20Analytics%20Case%20Study%20on%20Apple%20Customer%20Reviews%20Report.pdf)

---

*Project completed as part of the Bachelor of Business Analytics at the University of Newcastle, 2024.*
