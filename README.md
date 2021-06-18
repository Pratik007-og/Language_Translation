
# Language Translation

This is a NLP model using Recurrent Neural Networks to translate an input sequence in a particular Language(ex: english) to its equivalent sentence in another language(ex: French).
[Sequence to Sequence encoder decoder](https://towardsdatascience.com/understanding-encoder-decoder-sequence-to-sequence-model-679e04af4346) has been used to build the model.


## Data Collection

The dataset for translation can de downloaded from [here](http://www.manythings.org/anki/).
It contains datasets in the form of pairs of words in input language and corresponding word in target language.


  
## Encoder Decoder RNNs architecture 
Sequence to Sequence Encoder Decoder for Language Translation

![](https://github.com/Pratik007-og/Language_Translation/blob/main/eng-fra.jpg)<br>

![](https://github.com/Pratik007-og/Language_Translation/blob/main/seq2seq.png)

![]


## Pre-requisites
You need to be thorough with some concepts to clearly grasp how the model is working and the complete flow of input to the target.
These concepts are:

- Recurrent Neural Networks(RNN): [Theory](https://www.geeksforgeeks.org/introduction-to-recurrent-neural-network/), [Implementation](https://www.tensorflow.org/guide/keras/rnn)
- Word Embedding: [Theory](https://machinelearningmastery.com/what-are-word-embeddings/)
- Long Short Term Memory(LSTM): [Theory](https://www.geeksforgeeks.org/understanding-of-lstm-networks/), [Video](https://www.youtube.com/watch?v=eCvz-kB4yko)

If you want an in-depth intuition as to how each component works, you can read this [paper](https://arxiv.org/pdf/1909.09586v1.pdf).

  
