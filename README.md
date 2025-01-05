Detecting bias in news articles is a challenging task due to the nu-
anced and subtle ways bias can be expressed at the sentence level.
In this paper we evaluate the performance of several transformer-
based models, including BERT, RoBERTa, DistilBERT, and DeBERTa,
in addition to a state-of-the-art machine learning model, Support
Vector Machine (SVM), for the task of sentence-level bias detection.
The performance of the models is tested on a dataset specifically
designed for this purpose, using preprocessing techniques such as
text cleaning, and oversampling. We provide a comparative analysis
of different models for sentence-level bias detection.
Our results reveal that some transformer models outperform oth-
ers, with DistilBERT achieving the best overall performance by
balancing computational efficiency with high precision and recall.
Interestingly, a traditional machine learning approach like SVM
can perform better than certain types of transformer models. These
findings highlight the effectiveness of transformer models for bias
detection while also showing the potential of traditional machine
learning methods when combined with proper pre-processing.
