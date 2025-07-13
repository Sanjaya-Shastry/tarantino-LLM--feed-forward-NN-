# tarantino-LLM-NN

A simple character-level language model built without using RNNs or Transformers. Built in Google Colab using Keras, trained on movie scripts. As expected the output does not make much sense. 

Few features:
- Manual character-level tokenization
- Feedforward neural network:
  - Dense(512) → Dense(256) → Dense(39)
  - No RNNs, no Transformers
