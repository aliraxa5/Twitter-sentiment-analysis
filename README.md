# Twitter-sentiment-analysis
This repository contains a Twitter Sentiment Analysis project that utilizes Apache Spark (PySpark) for big data processing and NLP techniques for sentiment classification. The analysis is performed on the Sentiment140 dataset, where tweets are classified as positive or negative based on their sentiment.

 # Features

Big Data Processing with Apache Spark

NLP Pipeline (Text Cleaning, Tokenization, Stopword Removal)

Sentiment Classification using Logistic Regression

Feature Engineering with CountVectorizer

Data Visualization using Matplotlib & Seaborn

Model Evaluation (Accuracy, Precision, Recall, F1-score)

Notebook Deployment on Databricks

# Technologies & Libraries Used

Apache Spark (PySpark) – Distributed big data processing

Tweepy – Twitter API for real-time tweet extraction

TextBlob – NLP-based sentiment analysis

Matplotlib & Seaborn – Data visualization

Pandas – Data manipulation and analysis

Scikit-learn – Model evaluation & classification metrics

WordCloud – Visualization of frequently used words

Databricks – Cloud-based big data processing

Run on Databricks (Recommended for Big Data)

Upload SentimentAnalysis-Project.ipynb to Databricks.

Upload the dataset to /FileStore/tables/Sentiment140_CSV.csv.

Execute the notebook step by step in PySpark environment.

# Model Training & Evaluation

Data Preprocessing: Convert text to lowercase, remove special characters, stopwords.

Feature Engineering: CountVectorizer to convert text into numerical features.

Model Training: Logistic Regression using Spark ML.

Evaluation Metrics: Confusion Matrix, Accuracy, Precision, Recall, F1-score.

Visualization: WordCloud, Sentiment Distribution, and Feature Importance.
