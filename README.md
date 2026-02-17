Assignment 19: Word2Vec Text Embeddings

Project Overview
----------------
This assignment demonstrates the implementation of Word2Vec-based word embeddings for transforming textual data into dense numerical vector representations. The objective is to understand how semantic relationships between words can be captured using embedding techniques.

Objectives
----------
1. Understand limitations of traditional vectorization methods such as One-Hot Encoding and Bag of Words.
2. Learn the concept of word embeddings and distributed representations.
3. Implement Word2Vec using CBOW and Skip-Gram architectures.
4. Analyze word similarity and vector relationships.
5. Visualize learned embeddings using dimensionality reduction techniques.


Techniques Implemented
----------------------
- Text preprocessing and tokenization
- Word2Vec (CBOW model)
- Word2Vec (Skip-Gram model)
- Word similarity analysis
- Vector arithmetic operations
- Embedding visualization using PCA


Dataset
-------
SMS Spam Collection Dataset

Source:
https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset

The dataset contains SMS messages labeled as spam or ham and is used to train custom word embeddings.


Libraries Used
--------------
- pandas
- numpy
- nltk
- gensim
- scikit-learn
- matplotlib


Project Structure
-----------------
Assignment19_Word2Vec/
│
├── Assignment19_Word2Vec_Text_Embeddings.ipynb
├── spam.csv
└── README.txt


Execution Instructions
----------------------
1. Create and activate a Python virtual environment.
2. Install required libraries listed above.
3. Place the dataset file (spam.csv) inside the project directory.
4. Open the notebook using Jupyter Notebook or VS Code.
5. Select the project virtual environment as the kernel.
6. Run all cells sequentially.



