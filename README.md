Detecting Bias in News Articles
This repository contains code and models for detecting bias in news articles at the sentence level. The task of identifying bias is challenging due to the nuanced and subtle ways bias can be expressed in text. In this work, we evaluate several transformer-based models as well as a traditional machine learning approach to perform sentence-level bias detection.

Models Evaluated
The following models were evaluated for bias detection:

BERT (Bidirectional Encoder Representations from Transformers)
RoBERTa (A Robustly Optimized BERT Pretraining Approach)
DistilBERT (A Smaller, Faster, Cheaper, and Lighter version of BERT)
DeBERTa (Decoding-enhanced BERT with disentangled attention)
SVM (Support Vector Machine) - A traditional machine learning approach
Dataset and Preprocessing
The models were tested on a dataset specifically designed for sentence-level bias detection. Preprocessing techniques, such as text cleaning and oversampling, were applied to the data to improve the models' performance.

Key Results
DistilBERT achieved the best overall performance, balancing computational efficiency with high precision and recall.
Transformer models generally performed well, highlighting their effectiveness for bias detection in text.
Surprisingly, the SVM model outperformed certain transformer models, demonstrating that traditional machine learning approaches can still be competitive, especially when combined with the right preprocessing techniques.
Comparative Analysis
This repository also provides a comparative analysis of different models, allowing for a deeper understanding of how transformer models and traditional machine learning approaches differ in their ability to detect bias in news articles.
