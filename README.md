# EnhancedTF_IDF-model-
An enhanced TF-IDF-based model for accurate text summarization and classification, combining traditional statistical weighting with optimized preprocessing and contextual cues.


This project presents an enhanced TF-IDF (Term Frequency–Inverse Document Frequency) model designed for effective text summarization and classification. It builds upon the traditional TF-IDF algorithm by integrating advanced preprocessing, adaptive weighting, and contextual relevance mechanisms to generate more meaningful summaries and improve classification accuracy.

Features
-Improved keyword extraction using enhanced TF-IDF scoring
-Automatic text summarization preserving context
-Text classification using weighted features
-Preprocessing pipeline: tokenization, stopword removal, stemming
-Evaluation metrics: Precision, Recall, F1-score

How It Works
-Preprocess input documents (tokenize, clean, stem).
-Compute enhanced TF-IDF scores with dynamic weighting.
-Select top-ranked sentences for summarization.
-Use TF-IDF vectors for classification via models like SVM or Naive Bayes.

Dataset
=Used standard datasets like BBC News, 20 Newsgroups, and custom corpora.

Supports .txt or .csv formats.

 Technologies Used
-Python 
-Scikit-learn
-NLTK 
-Pandas, NumPy
-Matplotlib / Seaborn (for visualization)

Results
Higher classification accuracy due to cleaner vector representation.

Research Paper
This project is supported by an academic research paper titled:
Real-Time Text Classification and Summarization Model by Enhancing TF-IDF Extractive Summarization Method
https://ieeexplore.ieee.org/document/10861972 
