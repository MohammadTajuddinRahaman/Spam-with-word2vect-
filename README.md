# Spam-with-word2vect-
🧠 Spam Classification with Word2Vec
This project implements a spam detection system using Word2Vec embeddings and multiple machine learning classifiers. The model uses vector representations of words to capture the semantic meaning of text for more effective spam filtering.

📌 Project Highlights
Dataset: SMS messages labeled as spam or ham

Key Technique: Word2Vec from Gensim for word embeddings

No loops/functions – designed for readability and simplicity

Multiple classifiers used and compared

Visual performance comparison with a bar graph

🛠️ Workflow
Text Preprocessing:

Lowercasing, punctuation removal

Stopword removal

Tokenization

Word2Vec Embedding:

Trained a custom Word2Vec model using Gensim

Averaged vectors for each message (sentence vector)

Classification Models:

Logistic Regression

SVM

KNN

Naive Bayes

Random Forest (optional)

Evaluation:

Accuracy, Confusion Matrix

Bar graph for visual comparison

🧪 Models Compared
Classifier	                            Accuracy	F1 Score	Precision	Recall
Logistic Regression                        	✅	    ✅	      ✅    	✅
SVM	                                        ✅    	✅      	✅	    ✅
KNN	                                        ✅	    ✅      	✅    	✅
Naive Bayes	                                ✅    	✅	      ✅    	✅

📈 Output Includes

Word2Vec training confirmation

Transformed vector features

Accuracy scores of different classifiers

Confusion matrices

Performance bar chart

📚 Future Improvements
Pre-trained embeddings like GoogleNews Word2Vec

Use Deep Learning (LSTM/GRU) with word embeddings

Real-time SMS detection with Flask or Streamlit
