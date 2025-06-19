Task 1

## 🧾 Extended Description

This project delivers a structured analysis of transactional sales data collected from multiple coffee shop branches. It focuses on uncovering patterns in customer purchases and product performance across different geographic locations.
The dataset was queried from Google BigQuery using a custom SQL command to retrieve essential fields:

- `store_location`
- `transaction_qty`
- `product_category`
- `product_type`

This ensured a lean and relevant dataset, optimized for analysis.
The analysis was conducted using Microsoft Excel, where data cleaning and summarization were performed through a pivot table. This allowed for a comparative view of how different products perform in each store location.
 Objectives
- Identify top-selling product types and their regional demand.
- Compare sales performance across Hell's Kitchen, Lower Manhattan, and Astoria.
- Provide a baseline for inventory planning and marketing strategies.
 Findings
Barista Espresso** is the highest transacted item in **Lower Manhattan**, indicating strong customer preference.
Premium Beans** are uniquely popular in **Hell's Kitchen**, highlighting local taste variation.
Brewed Black Tea** and **Biscotti** show consistent sales across all three locations, suggesting broad appeal.
Task 2
This project performs sentiment analysis on the Amazon Fine Food Reviews dataset using deep learning techniques. It aims to classify customer reviews into three sentiment categories: positive, neutral, and negative. The model uses a Bidirectional LSTM (Long Short-Term Memory) neural network, which is particularly well-suited for analyzing sequential data such as text. LSTM is not a natural language processing (NLP) technique by itself; rather, it is a deep learning architecture commonly used in NLP tasks because of its ability to remember contextual information over long sequences. By combining NLP preprocessing steps like stopword removal and lemmatization with an LSTM-based classification model, the project is able to learn sentiment patterns in customer reviews. The result is a model capable of predicting the sentiment of new, unseen reviews with high accuracy. The project also includes data visualization, performance evaluation using classification metrics, and a sentiment prediction function that can be used for real-time sentiment classification.
