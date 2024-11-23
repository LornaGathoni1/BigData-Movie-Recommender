# BigData-Movie-Recommender
# Overview

This project is a content-based movie recommendation system that leverages TMDB metadata to suggest movies based on user preferences. The recommendation engine is built on a big data pipeline integrating Apache Kafka, Hadoop HDFS, and Apache Spark for scalability and efficiency.

#Goals

    Build a robust big data pipeline for processing TMDB data.
    Use machine learning models for personalized movie recommendations.
    Create a user-friendly interface with a Flask API for recommendations.
    Enable scalable storage and analysis using HDFS and Spark.

  # Key Features

    Real-Time Data Ingestion: Apache Kafka for streaming movie metadata.
    Distributed Storage: Hadoop HDFS for efficient data storage.
    Advanced Processing: Spark for cleaning, transformation, and model training.
    Machine Learning: Spark MLlib for recommendation modeling using cosine similarity.
    Interactive API: Flask API allows users to access recommendations.
    Visualization: Python libraries for data visualization.

  # Pipeline Architecture

    Data Ingestion: Kafka producers push TMDB data to Kafka topics.
    Data Storage: Data is saved in HDFS for fault-tolerant storage.
    Processing: Spark processes raw data, performs feature engineering, and trains the ML model.
    Recommendation Engine: A content-based model provides personalized movie suggestions.
    Deployment: Flask API serves movie recommendations and provides visualization for insights.

   # Technologies Used

    Apache Kafka: Real-time data streaming.
    Hadoop HDFS: Distributed data storage.
    Apache Spark: Data processing and ML model training.
    Spark MLlib: Cosine similarity for recommendations.
    Python: Data analysis and visualization.
    Flask: API deployment.
  # Dataset
     TMDB 5000 Movies and Credits dataset.
     Download TMDB dataset
  # Contributors
    List contributors with GitHub handles.
