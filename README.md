# seq2tax
A deep learning-based sequence classifier applied to 16S rRNA.

This repo builds further on the findings of [my bachelor's project](https://github.com/Lab-Vankerschaver/16S-ML-models) with the goal of creating a highly accurate, easy-to-use and easy-to-interpret sequence classification tool for the 16S rRNA gene but which can be applied and quickly re-trained to any marker gene.

Things to work on:
- additional data augmentation strategies (sequence cropping)
- creating combined model that takes in both k-mer and one-hot encoded sequences
- reduce training memory requirements by building a TensorFlow input pipeline ([tf.data](https://www.tensorflow.org/guide/data))
- create a [BERT-like](https://www.tensorflow.org/text/tutorials/classify_text_with_bert) multi-class & multi-label classifier
- do something about sequence entries with partially missing labels and how to weight the model around this problem...
