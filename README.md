# Automating Article Selection with Margin Insight

## Overview

In this project for MGTA 601 - Machine Learning for Business, I aimed to automate the article selection process for JS Media, targeting articles likely to garner over 1000 shares. This threshold is significant as articles with shares exceeding 1000 bring in considerably higher profits, yet each channel can only feature 12 such articles at a time.

## Data

The dataset includes 40,000 articles with 61 features covering a wide range of metrics, including keyword counts, digital media use, NLP metrics, and the timing of posts. The clean dataset retained all information, with 'Shares' serving as the target variable.

## Analysis & Results

Despite the median average shares per article being around 1400, no single feature strongly correlated with the number of shares. Through various model iterations, Random Forests emerged as the most accurate model with a 66% accuracy rate, outperforming K-Nearest Neighbors (KNN), which achieved 58%.

## Recommendations

The Random Forest model is recommended for deployment, predicting articles to collectively generate at least 11,200 shares, translating to approximately $12,400 in revenue per set of articles featured. This model not only enhances article selection efficiency but also offers greater insight into the profitability of articles.

## Reflections

This project underscores the potential of machine learning in streamlining media operations, specifically in maximizing the profitability of article selections. Future optimizations may include exploring additional algorithms or adjusting the share threshold to improve prediction accuracy.

---
