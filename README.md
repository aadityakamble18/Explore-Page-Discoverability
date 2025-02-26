# Explore Page Discoverability

## Overview
This project explores how different factors influence content discoverability on Instagram's Explore Page using machine learning techniques. By analyzing user interactions, comments, hashtags, and emojis, we aim to determine which parameters most effectively increase a post's reach.

## Table of Contents
- [Introduction](#introduction)
- [Problem Statement](#problem-statement)
- [Dataset](#dataset)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
- [Modeling](#modeling)
- [Results & Insights](#results--insights)
- [Limitations](#limitations)
- [Team](#team)

## Introduction
Understanding user engagement on social media is crucial for content creators and marketers. This project studies Instagram's Explore Page algorithms by analyzing various factors that contribute to content discoverability.

## Problem Statement
The objective of this project is to:
1. Analyze the factors influencing content appearance on Instagram's Explore Page.
2. Understand how Instagram’s algorithms impact content reach and visibility.
3. Develop machine learning models to predict content engagement and discoverability.

## Dataset
- The dataset was sourced from Kaggle and consists of **7488 rows** and **9 columns**.
- Important features include:
  - **User ID**
  - **Photo ID**
  - **Comments**
  - **Emoji Usage**
  - **Hashtags Used Count**
- The dataset was cleaned and preprocessed to handle missing values and format categorical data.

## Exploratory Data Analysis (EDA)
Key findings from EDA:
- Most users fall within the **50-100 User ID range**, with very few having more than 250.
- Posts with more unique **Photo IDs** tend to receive higher engagement.
- Hashtags significantly impact discoverability, with most comments using **1 or 2 hashtags**.
- Sentiment analysis of comments revealed that **99% were neutral**, with very few negative interactions.
- Users posting **longer comments** tend to engage more meaningfully.

## Modeling
We implemented two machine learning models to analyze the impact of different factors on content reach:
1. **Random Forest Classifier**
   - Used to predict whether an emoji would be used in a post.
   - Features considered: **Comment, User ID, Photo ID, Emoji Used, Hashtags Count**.
   - Provided feature importance insights.
2. **Decision Tree Classifier**
   - A simpler model used for comparison.
   - Visualized the decision-making process.

## Results & Insights
- **Emoji usage and hashtag count** were the most important factors influencing content reach.
- Surprisingly, the actual **content of the comment had little effect** on emoji usage.
- Feature importance analysis confirmed that **hashtags have a strong correlation with engagement**.
- Posts with **positive emojis** tend to have higher engagement and discoverability.

## Limitations
- The dataset is relatively **small** compared to real-world Instagram interactions.
- Instagram's **actual algorithm is complex and considers thousands of variables**, whereas we only analyzed a few key factors.
- The platform's algorithm is **constantly evolving**, making it difficult to generalize results over time.

## Team
- **Aditya Mundhada** 
- **Aaditya Kamble**
- **Vivek Saroj**

## Questions?
Feel free to open an issue or reach out to us for any inquiries!

---
**Note:** This project was developed as part of the IML Lab Project and is purely for research purposes.

