# text-generation-with-rnn

With the rise of generative AI, natural language generative systems became a hot interest for me. I decided to feed my curiosity by enrolling in DeepLearning.AI’s Natural Language Processing with Sequence Models which covered how the use of recurrent neural networks to generates the next-word on text data in one of the modules. In the spirit to put into practice what I have learnt, I decided to build my own text generator using Tensorflow and Keras.

## Text Generation with Gated Recurrent Units (GRUs)

This is a text generation project that uses stateful GRUs to train a character-level language model. This is where we feed text input data into the GRU and make it sample the next character of a sequence of previous characters, based on a probability distribution. The objectives of this project is to demonstrate:

1. How to process your input data for text generation with GRU?
2. How to use the Sequential API to build a text generator neural network architecture?
3. How sensible will the generated texts be?
4. Can we tune the models to be more conserve or diverse?

To make it more interesting, I decided to train the language model to generate texts from the bible! Although the generated texts are not reflective of the themes of the bible, and there was poor grammar choices, I was impressed by the frequency of correctly spelt words.

### Dataset

The dataset comprises of bible verses from the 66 books of the bible. You can use this [link](https://raw.githubusercontent.com/mxw/grmr/master/src/finaltests/bible.txt) to find the dataset used for this project.

### Resources

Chollet, F. (2017). Deep learning with python. Manning Publications.

Karpathy, A. (2015). The Unreasonable Effectiveness of Recurrent Neural Networks.

Brownlee, J. (2016). Text Generation With LSTM Recurrent Neural Networks in Python with Keras.

Brownlee, J. (2017). Stateful and Stateless LSTM for Time Series Forecasting with Python.

Tensorflow. (2023). Text Generation with an RNN.

Yumi. (2018). Stateful LSTM model training in Keras.
