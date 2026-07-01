# 📈 Market Sentiment Trader Behavior Analysis

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=700&size=30&duration=3000&pause=1000&color=00C853&center=true&vCenter=true&width=1000&lines=Market+Sentiment+Trader+Behavior+Analysis;Bitcoin+Fear+%26+Greed+Analytics;Hyperliquid+Trading+Behavior+Analysis;Python+%7C+Data+Analytics+%7C+Statistics;Portfolio+Project+by+Mohit+Singh" />

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&color=gradient&text=Market%20Sentiment%20Analysis&fontSize=40&fontAlignY=35&animation=fadeIn&fontColor=ffffff"/>

<br>

![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)

![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)

![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=for-the-badge)

![Seaborn](https://img.shields.io/badge/Seaborn-4C72B0?style=for-the-badge)

![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy)

![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

<br>

![License](https://img.shields.io/badge/License-MIT-green?style=flat-square)

![Maintained](https://img.shields.io/badge/Maintained-Yes-success?style=flat-square)

![Open Source](https://img.shields.io/badge/Open%20Source-Love-red?style=flat-square)

</div>

---

# 📖 Overview

Understanding **market psychology** is one of the most important aspects of financial trading.

This project investigates the relationship between **Bitcoin Market Sentiment** and **real-world trader performance** by integrating the **Bitcoin Fear & Greed Index** with **Hyperliquid historical trading data**.

Rather than analyzing market sentiment or trading behavior independently, this project combines both datasets to uncover behavioral patterns, profitability trends, trading activity, and risk-taking tendencies under different market conditions.

The project follows a complete **data analytics workflow**, including:

- Data Collection
- Data Cleaning
- Feature Engineering
- Dataset Integration
- Exploratory Data Analysis
- Statistical Analysis
- Business Insights
- Actionable Recommendations

---

# 🎯 Objectives

The primary objectives of this project are:

- Merge Bitcoin Market Sentiment with Hyperliquid Trading Data

- Clean and preprocess two independent datasets

- Analyze trader profitability under different market conditions

- Study changes in trading behavior during Fear and Greed markets

- Compare trader activity across sentiment regimes

- Perform statistical analysis to validate observed relationships

- Generate meaningful business recommendations

- Build a portfolio-ready Data Analytics project

---

# 📂 Dataset Description

This project combines two different datasets.

## 📊 Dataset 1 — Bitcoin Market Sentiment

The Fear & Greed Index represents the emotional state of the cryptocurrency market.

### Features

| Column | Description |
|----------|-------------|
| Date | Market Date |
| Timestamp | Unix Timestamp |
| Value | Fear & Greed Score |
| Classification | Extreme Fear, Fear, Neutral, Greed, Extreme Greed |

---

## 💹 Dataset 2 — Hyperliquid Historical Trading Data

Contains real trader activity.

### Features

| Column | Description |
|---------|-------------|
| Account | Trader ID |
| Coin | Cryptocurrency |
| Execution Price | Entry Price |
| Size Tokens | Quantity Traded |
| Size USD | Trade Size |
| Side | Buy / Sell |
| Closed PnL | Profit & Loss |
| Fee | Trading Fee |
| Timestamp | Trade Time |
| Direction | Trade Direction |

---

# 🚀 Problem Statement

Financial markets are strongly influenced by investor psychology.

One of the most widely used market psychology indicators is the **Fear & Greed Index**, which reflects whether investors are pessimistic or optimistic.

This project answers questions such as:

- Does trader profitability increase during Greed markets?

- Are traders more aggressive during Extreme Greed?

- Does Fear encourage more conservative trading?

- How does market sentiment influence trading volume?

- Does sentiment affect position sizing?

- Can market sentiment explain trading performance?

---

# 🏗 Project Architecture

```text
Bitcoin Fear & Greed Dataset
                │
                │
                ▼
        Data Cleaning
                │
                ▼
Historical Hyperliquid Trades
                │
                ▼
      Data Preprocessing
                │
                ▼
         Dataset Merge
                │
                ▼
 Exploratory Data Analysis
                │
                ▼
 Relationship Analysis
                │
                ▼
 Statistical Testing
                │
                ▼
 Business Insights
                │
                ▼
 Final Recommendations
```

---

# 🛠 Tech Stack

| Category | Technologies |
|------------|----------------|
| Programming Language | Python |
| Data Processing | Pandas |
| Numerical Computing | NumPy |
| Visualization | Matplotlib |
| Statistical Visualization | Seaborn |
| Statistical Analysis | SciPy |
| Development Environment | Jupyter Notebook |
| Version Control | Git & GitHub |

---

# 📁 Repository Structure

```text
market-sentiment-trader-behavior-analysis
│
├── data/
│   ├── raw/
│   │   ├── fear_greed_index.csv
│   │   └── historical_data.csv
│   │
│   └── processed/
│       └── merged_dataset.csv
│
├── notebooks/
│   └── trader_sentiment_analysis.ipynb
│
├── src/
│   ├── data_loader.py
│   ├── preprocessing.py
│   ├── feature_engineering.py
│   ├── analysis.py
│   ├── visualization.py
│   └── utils.py
│
├── images/
│
├── reports/
│
├── README.md
├── requirements.txt
├── LICENSE
└── .gitignore
```

---

# 📦 Project Workflow

```text
Raw Data
   │
   ▼
Data Collection
   │
   ▼
Data Cleaning
   │
   ▼
Feature Engineering
   │
   ▼
Dataset Merge
   │
   ▼
Exploratory Data Analysis
   │
   ▼
Relationship Analysis
   │
   ▼
Statistical Testing
   │
   ▼
Business Insights
```

---
# 📊 Exploratory Data Analysis (EDA)

The Exploratory Data Analysis (EDA) phase focuses on understanding both datasets individually and after merging them. This helps identify hidden patterns, anomalies, and behavioral trends before conducting deeper statistical analysis.

### Data Understanding

The following analyses were performed:

- ✔ Dataset Overview
- ✔ Missing Value Analysis
- ✔ Duplicate Detection
- ✔ Data Type Inspection
- ✔ Summary Statistics
- ✔ Date-Time Conversion
- ✔ Dataset Integration

---

## 📈 Exploratory Analysis Performed

### 📊 Market Sentiment Distribution

Analyzed the frequency of each sentiment class:

- Extreme Fear
- Fear
- Neutral
- Greed
- Extreme Greed

This helps understand the dominant market psychology during the observation period.

---

### 💰 Closed Profit & Loss Distribution

Studied trader profitability using:

- Histogram
- KDE Distribution
- Boxplot

Purpose:

- Detect outliers
- Understand profit/loss spread
- Analyze distribution skewness

---

### 💹 Position Size Analysis

Investigated:

- Average Position Size
- Median Position Size
- Position Size Distribution

This provides insights into trader risk appetite under different market conditions.

---

### 🔄 Trading Activity

Examined:

- Number of Trades
- Trading Volume
- Buy vs Sell Distribution
- Coin-wise Trading Activity

---

### 💵 Trading Fee Analysis

Measured:

- Average Trading Fee
- Total Fees
- Fee Distribution

Trading fees indirectly indicate trading frequency and position sizes.

---

# 📉 Relationship Analysis

The core objective of this project is to investigate how market sentiment affects trader behavior.

The following relationships were analyzed:

### ✔ Closed PnL vs Market Sentiment

Questions answered:

- Are traders more profitable during Greed?

- Does Extreme Fear reduce profitability?

- Which sentiment regime performs best?

---

### ✔ Position Size vs Sentiment

Investigated whether traders increase position size during optimistic markets.

Compared:

- Mean Position Size

- Median Position Size

- Position Size Distribution

---

### ✔ Trading Direction vs Sentiment

Studied whether traders prefer:

- BUY positions

or

- SELL positions

during different market conditions.

---

### ✔ Coin-wise Profitability

Compared profitability across different cryptocurrencies.

Measured:

- Total Closed PnL

- Average Closed PnL

- Trading Frequency

---

### ✔ Top Trader Analysis

Ranked traders based on:

- Total Profit

- Average Profit

- Number of Trades

- Average Position Size

This helps identify high-performing trading accounts.

---

# 📊 Statistical Analysis

Beyond visualization, statistical testing was performed to validate observed patterns.

---

## Correlation Analysis

Generated a correlation matrix between:

- Execution Price

- Position Size

- Closed Profit & Loss

- Trading Fees

The heatmap identifies linear relationships among numerical features.

---

## ANOVA Test

A one-way ANOVA test was conducted to determine whether trader profitability differs significantly across market sentiment categories.

### Null Hypothesis (H₀)

There is no significant difference in average trader profitability across different market sentiment regimes.

### Alternative Hypothesis (H₁)

At least one market sentiment category has a significantly different average profitability.

The p-value obtained from the ANOVA test determines whether market sentiment has a statistically significant influence on trader performance.

---

# 📸 Visualization Gallery

The project generates multiple visualizations.

## Market Analysis

- Market Sentiment Distribution
- Sentiment Percentage Pie Chart

---

## Profitability Analysis

- Closed PnL Distribution
- Average PnL by Sentiment
- Coin-wise Profitability

---

## Trading Behavior

- Buy vs Sell Distribution
- Position Size Distribution
- Trading Fee Distribution

---

## Statistical Analysis

- Correlation Heatmap
- Boxplots
- Distribution Plots

---

## Sample Outputs

| Visualization | Preview |
|--------------|---------|
| Sentiment Distribution | ![](images/sentiment_distribution.png) |
| Average PnL | ![](images/pnl_by_sentiment.png) |
| Position Size | ![](images/position_size.png) |
| Trading Direction | ![](images/trader_direction.png) |
| Correlation Heatmap | ![](images/correlation_heatmap.png) |

---

# 💡 Key Findings

The analysis revealed several interesting insights:

- Fear was the most frequently observed market sentiment.

- Trader profitability varied across different sentiment regimes.

- Position sizes changed depending on prevailing market psychology.

- Trading activity increased during optimistic market conditions.

- Larger trades generally incurred higher trading fees.

- Statistical testing suggested that market sentiment has a measurable impact on trading behavior.

---

# 💼 Business Recommendations

Based on the findings, the following recommendations are proposed:

### 📌 Risk Management

Incorporate market sentiment indicators into trading strategies to improve decision-making during highly volatile market conditions.

---

### 📌 Position Sizing

Adjust position sizes according to prevailing market sentiment to manage downside risk.

---

### 📌 Trading Strategy

Avoid emotionally driven decisions during periods of Extreme Fear and Extreme Greed.

---

### 📌 Portfolio Management

Combine market sentiment indicators with technical and fundamental analysis to improve investment decisions.

---

### 📌 Future Trading Systems

Integrate sentiment indicators as features in machine learning models for predictive analytics.

---
# ⚙️ Installation

Clone this repository:

```bash
git clone https://github.com/YOUR_GITHUB_USERNAME/market-sentiment-trader-behavior-analysis.git
```

Navigate into the project directory:

```bash
cd market-sentiment-trader-behavior-analysis
```

---

# 📦 Install Dependencies

Using pip:

```bash
pip install -r requirements.txt
```

or manually:

```bash
pip install pandas numpy matplotlib seaborn scipy jupyter
```

---

# ▶️ Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
notebooks/trader_sentiment_analysis.ipynb
```

Run all notebook cells sequentially to reproduce the analysis.

---

# 📂 Project Modules

| Module | Purpose |
|---------|---------|
| `data_loader.py` | Loads raw datasets |
| `preprocessing.py` | Cleans and preprocesses the datasets |
| `feature_engineering.py` | Creates derived analytical features |
| `analysis.py` | Performs exploratory and statistical analysis |
| `visualization.py` | Generates charts and plots |
| `utils.py` | Helper functions |

---

# 📊 Technologies Used

<div align="center">

| Technology | Purpose |
|------------|---------|
| 🐍 Python | Programming Language |
| 🐼 Pandas | Data Manipulation |
| 🔢 NumPy | Numerical Computing |
| 📈 Matplotlib | Visualization |
| 🎨 Seaborn | Statistical Visualization |
| 📊 SciPy | Statistical Analysis |
| 📓 Jupyter Notebook | Interactive Analysis |
| 🌐 Git & GitHub | Version Control |

</div>

---

# 📈 Future Improvements

The current project establishes a strong analytical foundation, with several opportunities for future enhancement.

### Planned Improvements

- 🚀 Interactive Streamlit Dashboard

- 📊 Plotly Interactive Visualizations

- 🤖 Machine Learning Prediction Model

- 📈 Time-Series Forecasting

- 🌐 Live Fear & Greed API Integration

- ⚡ Real-Time Hyperliquid API Integration

- 📉 Portfolio Risk Analytics

- 📊 Automated Report Generation

- ☁ Cloud Deployment

- 🧠 AI-powered Trading Recommendation Engine

---

# 🤝 Contributing

Contributions are always welcome.

If you have suggestions for improvements or would like to add new features:

1. Fork this repository
2. Create a new branch
3. Commit your changes
4. Push the branch
5. Open a Pull Request

---

# 📜 License

This project is licensed under the **MIT License**.

Feel free to use, modify, and distribute this project with proper attribution.

---

# 👨‍💻 Author

<div align="center">

# Mohit Singh

### 🎓 M.Sc. Data Analytics & Mathematical Methods

### 🤖 AI • Machine Learning • Data Analytics • Python

---

### 🌐 Connect With Me

<a href="https://www.linkedin.com/in/cptmohitsingh/" target="_blank">
<img src="https://img.shields.io/badge/LinkedIn-Mohit%20Singh-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

<br><br>

<a href="https://github.com/YOUR_GITHUB_USERNAME">
<img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github"/>
</a>

</div>

---

# ⭐ Support

If you found this repository helpful, consider supporting it by:

⭐ Starring the repository

🍴 Forking the project

📢 Sharing it with others

💡 Opening issues for suggestions or improvements

---

<div align="center">

# Thank You for Visiting!

### 📈 Data Analytics • Machine Learning • Financial Analytics

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=700&size=22&duration=3000&pause=1000&color=00C853&center=true&vCenter=true&width=700&lines=Thank+You+for+Visiting!;Happy+Coding!;Keep+Learning+Keep+Building!;Open+to+Collaborations!" />

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00C853,100:2962FF&height=150&section=footer"/>

</div>
