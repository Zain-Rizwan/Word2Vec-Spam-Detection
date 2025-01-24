# Word2Vec-Spam-Detection
This repository contains the solution to a text classification task: detecting spam messages using a custom-designed two-layer deep neural network and Word2Vec embeddings. All implementations are from scratch without using predefined libraries.

## Project Description
The goal of this project is to design and train a **two-layer deep neural network** for spam detection. The model uses **Word2Vec embeddings**, implemented with logistic regression and negative sampling, to represent words numerically.

## Dataset
The [Spam or Not Spam Dataset](https://www.kaggle.com/datasets/ozlerhakan/spam-or-not-spam-dataset?resource=download) is used in this project. It contains labeled messages for spam classification.

## Tasks Completed
1. **Data Preprocessing:**
   - Balanced the dataset to handle class imbalance.
   - Performed text cleaning and tokenization for Word2Vec embedding creation.

2. **Model Training:**
   - **Word2Vec:**
     - Implemented logistic regression with negative sampling for Word2Vec.
     - Generated embeddings of size 10 for words in the dataset.
   - **Neural Network:**
     - Designed a two-layer feed-forward neural network:
       - **Input Layer:** 12 words, each with embedding size 10.
       - **Hidden Layer:** 2 nodes, each of size 8.
       - **Output Layer:** 1 node (binary classification).

3. **Model Evaluation:**
   - Evaluated using metrics: accuracy, precision, recall, and F1 score.
   - Visualized results with a confusion matrix.

## Restrictions
- Predefined libraries for Word2Vec or neural network design were not used.

## Results
- **Performance Metrics:**
  - Accuracy
  - Precision
  - Recall
  - F1 Score
- **Confusion Matrix:** Visualized in the notebook.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/Zain-Rizwan/Word2Vec-Spam-Detection.git
