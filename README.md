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
### Content
- Word Segmentation
- Word to vector
