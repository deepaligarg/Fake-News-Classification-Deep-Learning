# Fake-News-Classification-Deep-Learning
A Deep Learning approach of classifying the news headlines and content as Fake or Real.

A considerable amount of labeled news headlines and content are taken and a Deep Learning approach is used to classify any news as Fake or Real.
Text pre-processing is done using **NLTK** library. The words are converted into vectors using **Word Embeddings**.
The model is built using **LSTM** and **Bi-directional LSTM** with **Dropout Layers**.

It was found that LSTM out-performed Bi-diectional LSTm for this use-case.
