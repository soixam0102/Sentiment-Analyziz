# Sentiment-Analyze

### Content
1. Word Segmentation
- Installation Vietnamese word segmentation by `VNLP core` [paper](https://arxiv.org/pdf/1709.06307v2.pdf)
- pip3 install vncorenlp

        mkdir -p vncorenlp/models/wordsegmenter
        wget https://raw.githubusercontent.com/vncorenlp/VnCoreNLP/master/VnCoreNLP-1.1.1.jar
        wget https://raw.githubusercontent.com/vncorenlp/VnCoreNLP/master/models/wordsegmenter/vi-vocab
        wget https://raw.githubusercontent.com/vncorenlp/VnCoreNLP/master/models/wordsegmenter/wordsegmenter.rdr
        mv VnCoreNLP-1.1.1.jar vncorenlp/ 
        mv vi-vocab vncorenlp/models/wordsegmenter/
        mv wordsegmenter.rdr vncorenlp/models/wordsegmenter/

2. Word to vector

- Word embedding with  IMDB data

    Base on embedding layer in the model, we build a vector for each word. Those vector have 64 dimentions.
    By using projector.tensorflow we have a visualization of word embedding.(upload meta.tsv and vect.tsv to that framework)

![img.png](img.png)