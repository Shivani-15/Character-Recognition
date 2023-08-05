# Character-Recognition
This repository contains implementations of sequential classifiers using Long Short-Term Memory (LSTM) and Recurrent Neural Network (RNN) for recognizing handwritten characters from Kannada/Telugu scripts.

### Dataset ###
This dataset consists of subset of  5 handwritten characters from Kannada/Telugu script. Each character is seen as sequence of 2-dimensional points (x and y coordinates) of one stroke of character (pen down to pen up).

### Problem Statement ###
To classify the characters
<br> <br>
**Model** : Since the characters are expressed as sequential coordinates, the problem statement requires a sequential model for classification. RNN and LSTM models are built and their performance is compared.

### Requirements
To run the code and experiments in this repository, you will need the following dependencies:

Python 3.x <br>
TensorFlow <br>
Keras <br>
NumPy <br>
Matplotlib (for visualization) <br>
