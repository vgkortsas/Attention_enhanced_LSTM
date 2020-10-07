# Attention enhanced LSTM network to translate dates

My own implementation of an LSTM encoder-decoder architecture with attention mechanism. I applied the architecture to translate dates from human readable format to machine readable format, achieving accuracy of 80% on the testing set.

## Project
Translate dates from human readable format ("3 May 1979", "5 April 09") to machine readable format ("1979-05-03", "2009-04-05").
([Jupyter Notebook](https://nbviewer.jupyter.org/github/vgkortsas/Attention_enhanced_LSTM/blob/master/Attention_mechanism_translate_dates.ipynb))

The project is based on the programming assignment of deeplearning.ai, course Sequence models, Neural machine translation with attention. It was implemented in Keras and I reimplemented it using TensorFlow 1.14.

## Requirements
A full list of the requirements is given [here](https://github.com/vgkortsas/Attention_mechanism_translate_dates/blob/master/requirements.txt). The Python and deep learning library versions are:
- Python 3.5.5
- TensorFlow 1.14.0

## Reference
[deeplearning.ai Sequence models](https://www.coursera.org/learn/nlp-sequence-models)




