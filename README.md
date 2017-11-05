# English to French Translator


Neural machine translator for English2French translation.

## Overview
This project is about translation from English to French language. That is accomplished by using TensorFlow library, more specifically it utilizes embedding with attention sequence-to-sequence RNN model. The dataset is text files of ~140,000 fairly simple sentences in English and in French.

This is made possible by the simple but powerful idea of the sequence to sequence network, in which two recurrent neural networks work together to transform one sequence to another. An encoder network condenses an input sequence into a vector, and a decoder network unfolds that vector into a new sequence.

<img src="http://pytorch.org/tutorials/_images/seq2seq.png">

### Files

[Jupyter Notebook](https://github.com/hparik11/language-translation/blob/master/language_translation.ipynb)

### Hyperparameters

Hyperparameter          | Number |
----------------------- | ------ |
Epochs                  | 5     |
Batch size              | 128    |
RNN size                | 128    |
LSTM layers             | 2      |
Encoding embedding size | 128    |
Decoding embedding size | 128    |
Learning rate           | 0.01  |
Keep probability        | 0.8    |

## Dataset

[WMT10 French-English corpus](http://www.statmt.org/wmt10/training-giga-fren.tar)
