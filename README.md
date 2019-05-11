The project experiment is separated into 3 parts.

The first part is in the first notebook, stockRandForest. It requires Sklearn.

The second part is word2vecRNN. To run this notebook, packages needed are:
- NLTK
- Sklearn
- gensim
- pytorch  

The pretrained word2vec model(`GoogleNews-vectors-negative300.bin`) is needed. The pretrained word2vec can be found at: https://s3.amazonaws.com/dl4j-distribution/GoogleNews-vectors-negative300.bin.gz.

The last part is BERT_GRU. Besides libraries used above, we used bert-as-service(https://github.com/hanxiao/bert-as-service) to extract sentence embeddings. 