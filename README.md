# Offensive_Language_Detection_Roman_Urdu

Roman Urdu Offensive Language Detection
Description
This project focuses on detecting offensive language in Roman Urdu using Machine Learning (ML) and Deep Learning (DL) techniques. It utilizes advanced embeddings like Word2Vec and fastText to enhance the performance of predictive models.
Features
•	Traditional ML Models: Includes Logistic Regression, Naive Bayes, SVM, Random Forest, and others.
•	Deep Learning Models: Implements Bi-LSTM and other architectures with pre-trained embeddings.
•	Embeddings: Supports Word2Vec and fastText.
•	Metrics: Evaluates performance using accuracy, F1-score, precision, and recall.
Results
•	ML Models: Logistic Regression and SVM provided the highest accuracy with TF-IDF vectorization.
•	DL Models: Bi-LSTM with Word2Vec achieved the highest F1-Score of 98%.
•	Visualization: Bar charts for comparative analysis of models' performance.
How to Run
1.	Clone the repository.
2.	Place dataset.csv in the root directory.
3.	Update paths for Word2Vec and fastText embeddings.
4.	Execute the script using python main.py.
Dependencies
•	pandas
•	numpy
•	scikit-learn
•	tensorflow
•	keras
•	gensim
•	matplotlib
•	texttable
This consolidated code and report provide an end-to-end pipeline for training and evaluating models on Roman Urdu datasets.
