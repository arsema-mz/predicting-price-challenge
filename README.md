# Financial News and Stock Price Integration Dataset Analysis

## Overview
This project involves exploratory data analysis (EDA) on the Financial News and Stock Price Integration Dataset (FNSPID). The aim is to analyze financial news articles and their impact on stock prices, providing insights that could aid in stock market predictions.

## Objectives
- Obtain descriptive statistics for headline lengths and publication trends.
- Analyze common keywords and phrases using natural language processing (NLP).
- Examine publication frequency over time and identify significant spikes.
- Assess publisher contributions and analyze the types of news reported.
- Explore the correlation between news sentiment and stock price movements.

## Dataset
The dataset consists of:
- **headlines**: Titles of financial news articles.
- **url**: Links to the full articles.
- **publisher**: Source of the articles.
- **date**: Publication date of the articles.
- **stock**: Associated company ticker symbols.

## Methodology
1. **Data Loading**: Loaded the dataset into a pandas DataFrame.
2. **Descriptive Statistics**: Analyzed headline lengths, article counts per publisher, and publication dates.
3. **Text Analysis**: Used NLP techniques to identify common keywords and phrases.
4. **Time Series Analysis**: Analyzed publication frequency over time.
5. **Publisher Analysis**: Identified the most active publishers and analyzed their contributions.
6. **Sentiment Analysis**: Conducted sentiment analysis on news headlines to quantify the tone of articles.
7. **Stock Movement Analysis**: Calculated daily stock returns and explored the correlation between sentiment scores and stock movements.

## Results
- Summary of key findings from the analysis, including:
  - Average headline length.
  - Most active publishers.
  - Notable publication trends.
  - Common keywords identified through NLP.
  - Correlation between news sentiment and stock returns.

## Challenges
- Data quality issues, including missing values and inconsistencies.
- Complexity in implementing NLP techniques for keyword extraction.
- Handling time series data and date formats.
- Analyzing the relationship between sentiment and stock movements.

## Conclusion
The analysis provided valuable insights into the relationships between financial news and stock market behavior. Findings indicate that while sentiment scores fluctuate, they do not consistently predict stock movements. The results can inform further research and predictive modeling efforts.

## Installation
To run this project, ensure you have the following installed:
- Python 3.x
- Pandas
- Matplotlib
- Seaborn
- NLTK or scikit-learn (for NLP tasks)

## Usage
Clone the repository and navigate to the project directory:
```bash
git clone https://github.com/arsema-mz/predicting-price-challenge
cd predicting-price-challenge