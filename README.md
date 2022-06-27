In this project we deal with two tasks -
1. Predict if the text is humorous or not, a binary classification
2. If it is humorous predict if the text is humor controversial or not

This project used dataset from Hahackathon (https://competitions.codalab.org/competitions/27446)

From the above mentioned hackathon, we performed 1a and 1c tasks.

The sentence embeddings are generated using BERT transformer and ELMo Bi-LSTM language model.

Th classification performance was compared between ELMo, BERT and ELMo + BERT embeddings.

F1-score is used as performance metric.
