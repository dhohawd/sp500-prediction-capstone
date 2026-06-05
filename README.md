S&P 500 Stock Price Prediction — MBAI Capstone Project

Dual-output stock prediction system combining deep learning, sentiment analysis, and financial validation
Ontario Tech University · MBAI 5600G · 2026


📌 Project Overview
Stock price movement is influenced by both quantitative patterns in historical data and qualitative signals from financial news. This project builds a dual-output prediction system that forecasts S&P 500 stock prices and movement direction simultaneously, combining five deep learning and machine learning models with FinBERT-based sentiment analysis.
The goal is to produce predictions that are not only statistically accurate but also financially meaningful — evaluated using metrics that reflect real investment decision-making.

🎯 Research Questions

Can a hybrid deep learning architecture outperform individual models for stock price forecasting?
Does incorporating financial news sentiment (via FinBERT) improve prediction accuracy?
Which model best balances statistical accuracy with financial validation metrics?


🤖 Models
ModelTypeKey StrengthLSTM + GRU HybridDeep learningCaptures both short and long-term dependenciesBiLSTMDeep learningBidirectional context from sequence dataCNN + LSTMDeep learningLocal pattern extraction + temporal modellingTime Series TransformerDeep learningAttention-based long-range dependency captureRandom ForestMachine learningInterpretable baseline with feature importance

🧠 Sentiment Layer
Financial news headlines are processed using FinBERT (a BERT model fine-tuned on financial text) to produce sentiment scores (positive / neutral / negative) that are incorporated as features alongside price and volume data.

📊 Evaluation Approach
Models are evaluated on both statistical and financial metrics:

Statistical: RMSE, MAE, directional accuracy
Financial: Simulated return, Sharpe ratio, maximum drawdown

This dual validation ensures predictions are useful for real-world decision support, not just benchmark performance.

🗂️ Repository Structure
├── milestone-1-proposal/
│   └── project_proposal.pdf
├── milestone-2-literature-review/
│   └── literature_review.pdf
├── milestone-3-eda/
│   ├── eda_notebook.ipynb
│   └── genetic_algorithm_feature_selector.ipynb
├── milestone-4-modelling/          ← in progress
├── milestone-5-final/              ← upcoming
├── models/                         ← model scripts and weights
├── sentiment/                      ← FinBERT pipeline
├── data/
│   └── README.md                   ← data sources and access instructions
└── README.md

🚦 Project Status
MilestoneTitleStatusCompleted1Project Proposal✅ DoneJan 20262Literature Review (26 references)✅ DoneFeb 20263EDA & Dimensionality Reduction✅ DoneMar 20264Model Development & Training🔄 In progress—5Final Report & Presentation⏳ Upcoming—

🛠️ Tech Stack
CategoryToolsLanguagesPythonDeep learningTensorFlow / KerasMachine learningScikit-learnSentiment analysisFinBERT (HuggingFace Transformers)Data processingPandas, NumPyVisualizationMatplotlib, SeabornFeature selectionCustom Genetic AlgorithmEnvironmentGoogle Colab

📁 Data
Stock price data sourced from public financial APIs (Yahoo Finance / Alpha Vantage). News headline data collected for sentiment analysis. See data/README.md for full details on data sources and how to reproduce the dataset.

Raw data files are not included in this repository due to size and licensing constraints.


👥 Team
NameContributionsDhohaEDA, dimensionality reduction, genetic algorithm feature selector, overall architectureShivamModel development, FinBERT sentiment pipeline, financial validation metrics

📚 Academic Context
Capstone project for MBAI 5600G, Master of Business Analytics and AI
Ontario Tech University · Winter/Spring 2026
Literature review covers 26 peer-reviewed references spanning deep learning for time series, NLP in finance, and financial model evaluation frameworks.

📬 Contact
Dhoha
Master of Business Analytics and AI · Ontario Tech University
LinkedIn · GitHub · Email
