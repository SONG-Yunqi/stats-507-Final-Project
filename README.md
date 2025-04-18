# STATS 507 Final Project
This repository is for STATS 507 final project. The project name is 'Sentiment Classification for Amazon Product Reviews Based on Deep Learning Method'. The abstract is shown below.

Abstract—This project explores sentiment classification of
 Amazon product reviews using deep learning methods. Using the
 ’amazon-polarity’ dataset, the project trains and evaluates the
 performance of a baseline TF-IDF+LinearSVC model, GloVe
based LSTM and TextCNN models, and a BERT model. The
 results demonstrate that deep learning methods significantly
 outperform traditional machine learning approaches across ac
curacy, F1 score, and AUC metrics. Among all models, BERT
 achieves the highest performance, confirming its strength in
 capturing contextual and semantic nuances in text. While BERT
 incurs the highest computational cost, the LSTM model emerges
 as a strong alternative for resource-constrained scenarios. This
 study emphasizes the practical effectiveness of modern NLP
 architectures for real-world text classification tasks.

 In this repository, there is a 'final_project.ipynb' file, which contains the python code for the project. And there is a pdf file containing the summary report for my project.

 Warning: The code uses the module 'gensim', you may have to **downgrade numpy and scipy**. After install the modules, you may have to **restart**. Otherwise, you may encounter ImportError.
