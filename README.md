# Character_Text_Recognition_RNN
A recurrent neural network for  sequence character recognition from text files, transcription and generation.
This notebook contains the implementation of an LSTM-RNN(Long Short Term Memory recurrent neural network). The network is trained on tons of text characters from a text file and is capable of generating new text character by character. 

This network is based off of Andrej Karpathy's [post on RNNs](http://karpathy.github.io/2015/05/21/rnn-effectiveness/) and [implementation in Torch](https://github.com/karpathy/char-rnn). Below is the general architecture of the character-wise RNN.


