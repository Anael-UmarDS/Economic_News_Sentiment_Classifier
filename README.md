# Economic News Sentiment Classifier

## Author

Anael Umar

**GitHub**: [Anael-UmarDS](https://github.com/Anael-UmarDS)

---

## Description

This project pulls **real-time economic headlines** from [NewsAPI](https://newsapi.org) and automatically labels them using **VADER sentiment analysis**. It then trains a **logistic regression classifier** to categorize future headlines as **positive**, **neutral**, or **negative**. The final output includes evaluation metrics and trend **plots** to visualize **sentiment shifts** over time.

---

## Objectives

- Applying machine learning to understand **live financial data**
- Automate labeling of economic headlines using **natural language processing (NLP)** tools
- **Visualize** economic sentiment trends over a strict period of time
- Provide a **foundation** for further research in economic forecasting and AI-based sentiment analysis
- **Applying machine learning** to understand the economy at a **macroeconomic level**

---

## How It Works

1. **Data Fetching**  
   Headlines are fetched using the NewsAPI for the keyword **economy**.

2. **Auto-labeling with VADER**  
   Each headline is scored using VADER sentiment analysis and categorized into:
   - **positive**
   - **neutral**
   - **negative**

3. **Training a Classifier**  
   A logistic regression model is trained on the auto-labeled data using TF-IDF features.

4. **Evaluation**  
   The model is evaluated using accuracy, precision, recall, F1-score, and a confusion matrix.

5. **Visualization**  
   Plots are generated to track:
   - Percentage of each sentiment by week
   - Sentiment trends over time for economic headlines

---

## Example Use Cases

- Predicting **market mood shifts** based on economic news sentiment
- **Tracking** government or policy-related economic tone
- Training ML pipelines with **auto-labeled** real-world data
- Demonstration of **applied machine learning** and **NLP**

---

## Visual Outputs

- **Confusion Matrix**
- **Line Charts** of Sentiment Percentage per Week  
- Real world **demo headlines** pulled from Google News for testing

---
## Limitations

- **Headline Context**: Headlines lack full article context, which could influence sentiment accuracy
- **Bias**: Certain media sources may exhibit political or economic bias that skews sentiment labeling
- **Imbalanced Labels**: Economic headlines are often skewed toward neutral sentiment, which can affect model generalization
- **Query Limit for Free Developer Plan**: The API free Developer plan only allows up to 100 requests per day and only articles up to a month old, therefore forcing training data to be short and visualization to plot weekly headline percentage over a total of 1 month
---

## Setup Instructions

1. Get your free NewsAPI key by going to https://newsapi.org or clicking the link above in **Description**
2. Click **"Get API Key"** and register with your information
3. Replace your key in the cell under **API Setup** with where it says **"YOUR KEY HERE"**
4. Run the notebook in Jupyter Labs, Google Colab, or in a Python file

---

## Conclusions

- **Sentiment classification** on news headlines is feasible using lightweight models
- **Weekly sentiment trends** can uncover **mood shifts** in the economy
- Even rule-based systems like **VADER** can support training useful **supervised models**
- The classifier achieved **reasonable performance** in identifying headline sentiment automatically

---

## Implications

###Financial Markets

- **Investor Sentiment Monitoring**: Investigate market mood in real-time
- **Event-Driven Trading**: Identify spikes in optimism or fear to adjust strategy

###Public Policy

- **Macroeconomic Tracking**: Understand how the media presents economic news
- **Crisis Detection**: Spot growing negative trends in headlines

###ML Development

- **Semi-Supervised Learning**: Demonstrates how to bootstrap datasets from unlabeled text
- **Fine-Tuning Opportunity**: Base model could be improved using deep learning

---

## Machine Learning Concepts

- API
- Natural Language Processing (NLP)
- Feature Engineering
- Model Training & Evaluation
- Data Visualization
