# sNLP_project_2019
UCL Statistical Natural Language Processing Project

Contents:

1) Project Report
2) Project Poster
3) Code folder containing .ipynb files

Below are the notebooks
----------------------------------------------------

1) Demonstration notebook
2) Create datasets.ipynb
3) Finetune BERT - find best hyperparameters.ipynb
4) Check BERT hyperparameters.ipynb
5) Finetune BERT for test set.ipynb 
6) SARC bag of words.ipynb
7) Sentence Embeddings - GloVe.ipynb
8) Sentence Embeddings ELMo.ipynb
9) ELMO_TFhub.ipynb

----------------------------------------------------

1) Requested Colab notebook so that markers can experiment with our models
2) Creates the 100/50/25/12.5/6.25% project training sets
3) Used to fine-tune BERT to find the best hyperparamters
4) Used to review the results of (3)
5) Used to fine-tune BERT using the results from (3) and (4) and get metrics on the test set
6) Applies a logistic regression classifier to Bag-of-Words features, and calculated the metrics on the test set
7) As with (6), but using sentence embeddings derived from GloVe word embeddings as features
8) As with (6), but using sentence embedding derived from a prrtained ELMo model as features \9)-11) Code and results from out initial attempt at using ELMo from TFhub and a dense layer as the classifier. 
