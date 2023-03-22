# Bangla Fake News Detection using Machine Learning and Deep Learning

This project is based on the research paper titled "A Study Towards Bangla Fake News Detection Using Machine Learning and Deep Learning" by Hossain et al. The aim of the project is to identify Bangla fake news articles using machine learning and deep learning techniques.

## Requirements

The following libraries are required to run the code:

- Tensorflow 2.0 or higher
- Keras
- Scikit-learn
- Pandas
- Numpy

## Dataset

The researchers used a corpus of 57,000 Bangla news articles related to trustworthiness and counterfeit to train their models. The dataset is not included in this repository but can be obtained by contacting the authors.

## Models

The study used two deep learning models, Bi-LSTM with Glove and FastText embeddings, and a state-of-the-art model, Gated Recurrent Unit (GRU). The models were evaluated using K-fold cross-validation and achieved accuracy scores of 95% and 94% for Bi-LSTM with Glove and FastText, respectively. The GRU model achieved an accuracy score of 77%.

## References

Hossain, E., Nadim Kaysar, M., Jalal Uddin Joy, A.Z.M., Mizanur Rahman, M., Wahidur Rahman (2022). A Study Towards Bangla Fake News Detection Using Machine Learning and Deep Learning. In: Shakya, S., Balas, V.E., Kamolphiwong, S., Du, KL. (eds) Sentimental Analysis and Deep Learning. Advances in Intelligent Systems and Computing, vol 1408. Springer, Singapore. https://doi.org/10.1007/978-981-16-5157-1_7
