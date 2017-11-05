# English to French Translator


Neural machine translator for English2French translation.

## Overview
This project is about translation from English to French language. That is accomplished by using TensorFlow library, more specifically it utilizes embedding with attention sequence-to-sequence RNN model. The dataset is text files of ~140,000 fairly simple sentences in English and in French.

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
