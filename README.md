<a target="_blank" href="https://colab.research.google.com/github/giuseppe-tanzi/Part-Of-Speech-Tagging/blob/main/POS_Tagging.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

# Part-of-speech tagging


Authors:
- [Yuri Noviello](https://github.com/yurinoviello)
- [Enrico Pallotta](https://github.com/PallottaEnrico)
- [Flavio Pinzarrone](https://github.com/flaviopinzarrone)
- [Giuseppe Tanzi](https://github.com/giuseppe-tanzi)

[First assignement](./Assignment.ipynb) for the "Natural Language Processing" course of the Artificial Intelligence master's degree at University of Bologna.

## Abstract

In Natural Language Processing, it is important the use of part-of-speech tagging. By assigning each word a specific tag, algorithms can improve the representation of similar words in different situations. The objective of this study is to tackle part-of-speech tagging with bidirectional recurrent neural models with a small number of parameters. Different networks with different combinations of layers were compared, using recurrent networks such as BiLSTM and BiGRU. The embedding was pre-trained using GloVe-50 and the Out-Of-Vocabulary words were initialized by taking the average of a 3-words context. The two best models, which contained BiLSTM layer, both achieved a Macro-F1 scores of 0.77.

## Dataset

For this experiment, the Dependency Parsed Treebank dataset by University of Pennsylvania is used. It contains 199 documents annotated, but in oder to achieve better results each document is been splitted into sentences: 1958 sentences for the training set, 1242 for the validation set and 628 for the test set.

## Resources and references

- [TensorFlow](https://www.tensorflow.org/?hl=it)
- [Sklearn](https://scikit-learn.org/stable/)
- [Dependency Parsed Treebank dataset](https://www.nltk.org/nltk_data/)
