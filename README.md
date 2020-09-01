# Semantic Similarity Library

This library include Wikipedia link-based and word embedding-based algorithms to measure semantic similarity. 

Install the required dependencies using
```
pip install -r requirements.txt
```


For word embedding-based approach please add the word embedding models in the `Word_embedding/data` folder. 

Some pretrained models can be obtained from:
[Word2Vec](https://github.com/mmihaltz/word2vec-GoogleNews-vectors)
[GloVe](https://nlp.stanford.edu/projects/glove/)
[FastText](https://fasttext.cc/docs/en/pretrained-vectors.html)

Note that the Glove model needed to be transformed into word2vec format. Refer this [link](https://radimrehurek.com/gensim/scripts/glove2word2vec.html)
