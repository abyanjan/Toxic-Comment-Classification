# Toxic-Comment-Classification

The is a text classification problem performed on solving the [**Toxic Comment Classification**](https://www.kaggle.com/c/jigsaw-toxic-comment-classification-challenge/overview) Challenge at Kaggle.

-As a multi-label classification task, different appraoches are applied to solving the problem.
- For text vectorization, bag of words and word embeddings are applied

**Modeling Approaches**
- Binary Relevance 
- Classifier Chain
- LSTM
- Transfer Learning with BERT

**Libraries**
- pandas==1.1.5
- numpy==1.19.5
- matplotlib
- seaborn==0.11.1
- scikit-learn
- scikit-multilearn==0.2.0
- texthero==1.0.9
- wordcloud==1.8.1
- gensim==3.6.0
- tensorflow==2.4.1
- tensorflow-hub==0.11.0
- tensorflow-text==2.4.3
- tf-models-official==2.4.0

The final score obtained with BERT model at Kaggle is mean AUC ROC score of **0.98172**
