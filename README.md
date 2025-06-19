-Data Extraction
-The following SQL query was used to extract the necessary columns from BigQuery:
SELECT 
  store_location, 
  transaction_qty,
  product_category, 
  product_type
FROM `silent-kite-449818-c3.Brainwave_task_1.coffee shop sales`
GROUP BY 
  store_location, 
  transaction_qty,
  product_category, 
  product_type
ORDER BY 
  transaction_qty DESC;
Task 2
This project performs sentiment analysis on the Amazon Fine Food Reviews dataset using deep learning techniques. It aims to classify customer reviews into three sentiment categories: positive, neutral, and negative. The model uses a Bidirectional LSTM (Long Short-Term Memory) neural network, which is particularly well-suited for analyzing sequential data such as text. LSTM is not a natural language processing (NLP) technique by itself; rather, it is a deep learning architecture commonly used in NLP tasks because of its ability to remember contextual information over long sequences. By combining NLP preprocessing steps like stopword removal and lemmatization with an LSTM-based classification model, the project is able to learn sentiment patterns in customer reviews. The result is a model capable of predicting the sentiment of new, unseen reviews with high accuracy. The project also includes data visualization, performance evaluation using classification metrics, and a sentiment prediction function that can be used for real-time sentiment classification.
