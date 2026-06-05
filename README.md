# S&P 500 Stock Price Prediction — MBAI Capstone Project

> Dual-output stock prediction system combining deep learning, sentiment analysis, and financial validation
> **Ontario Tech University · MBAI 5600G · 2026**

---

## Project Overview

Stock price movement is influenced by both quantitative patterns in historical data and qualitative signals from financial news. This project builds a **dual-output prediction system** that forecasts S&P 500 stock prices and movement direction simultaneously, combining five deep learning and machine learning models with FinBERT-based sentiment analysis.

The goal is to produce predictions that are not only statistically accurate but also **financially meaningful** — evaluated using metrics that reflect real investment decision-making.

---

## Research Questions

1. Can a hybrid deep learning architecture outperform individual models for stock price forecasting?
2. Does incorporating financial news sentiment (via FinBERT) improve prediction accuracy?
3. Which model best balances statistical accuracy with financial validation metrics?

---

## Models

| Model | Type | Key Strength |
|---|---|---|
| LSTM + GRU Hybrid | Deep learning | Captures both short and long-term dependencies |
| BiLSTM | Deep learning | Bidirectional context from sequence data |
| CNN + LSTM | Deep learning | Local pattern extraction + temporal modelling |
| Time Series Transformer | Deep learning | Attention-based long-range dependency capture |
| Random Forest | Machine learning | Interpretable baseline with feature importance |

---

## Sentiment Layer

Financial news headlines are processed using **FinBERT** (a BERT model fine-tuned on financial text) to produce sentiment scores (positive / neutral / negative) that are incorporated as features alongside price and volume data.

---

## Evaluation Approach

Models are evaluated on both statistical and financial metrics:

- **Statistical:** RMSE, MAE, directional accuracy
- **Financial:** Simulated return, Sharpe ratio, maximum drawdown

This dual validation ensures predictions are useful for real-world decision support, not just benchmark performance.

---

## Repository Structure
├── milestone-1-proposal/
│   └── project_proposal.pdf
├── milestone-2-literature-review/
│   └── literature_review.pdf
├── milestone-3-eda/
│   ├── eda_notebook.ipynb
│   └── genetic_algorithm_feature_selector.ipynb
├── milestone-4-modelling/
├── milestone-5-final/
├── models/
├── sentiment/
├── data/
│   └── README.md
└── README.md

---

## Project Status

| Milestone | Title | Status | Completed |
|---|---|---|---|
| 1 | Project Proposal | Done | Jan 2026 |
| 2 | Literature Review (26 references) | Done | Feb 2026 |
| 3 | EDA and Dimensionality Reduction | Done | Mar 2026 |
| 4 | Model Development and Training | In progress | — |
| 5 | Final Report and Presentation | Upcoming | — |

---

## Tech Stack

| Category | Tools |
|---|---|
| Languages | Python |
| Deep learning | TensorFlow / Keras |
| Machine learning | Scikit-learn |
| Sentiment analysis | FinBERT (HuggingFace Transformers) |
| Data processing | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Feature selection | Custom Genetic Algorithm |
| Environment | Google Colab |

---

## Data

Stock price data sourced from public financial APIs (Yahoo Finance / Alpha Vantage). News headline data collected for sentiment analysis. See data/README.md for full details.

Raw data files are not included in this repository due to size and licensing constraints.

---

## Team

| Name | Contributions |
|---|---|
| Dhoha | EDA, dimensionality reduction, genetic algorithm feature selector, overall architecture |
| Shivam | Model development, FinBERT sentiment pipeline, financial validation metrics |

---

## Academic Context

Capstone project for **MBAI 5600G**, Master of Business Analytics and AI
Ontario Tech University · Winter/Spring 2026

---

## Contact

**Dhoha**
Master of Business Analytics and AI · Ontario Tech University
[LinkedIn](#) · [GitHub](#) · [Email](#)
