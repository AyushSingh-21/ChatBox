# ChatBox
Neural Machine Translation (NMT) - Translating English sentences to Marathi sentences

Machine Translation refers to translating phrases across languages using deep learning and specifically with RNN ( Recurrent Neural Nets ). Most of these are complex systems that is they are a combined system of various algorithms. But, at its core, NMT uses sequence-to-sequence ( seq2seq ) RNN cells. Such models could be character level but word level models remain common.


We will basically create an encoder-decoder LSTM model using Keras Functional API). We will convert the English sentences to Marathi ( A language native to India ). But, why Marathi?

Has special characters and much complex.
Has a totally new script ( Devnagiri ) with no pretrained word-embeddings available yet.
Here's an example,

the cat sleeps among the dogs -> मांजर कुत्रींमध्ये झोपतात

So, let's get started.
