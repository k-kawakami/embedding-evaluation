# embedding-evaluation
Evaluation tool for word embeddings

## Wordsim Task
Wordsimilarity task is commonly used as a evaluation method for word-embeddings such as Word2vec, Glove.
This task investigate how your vector capture semantics between word pairs.

Wordsim task can be run on english, spanish, and french wordembeddings.

```
python wordsim.py -l en -v vector_file.txt
```

Your vector file to satisfy the following form.
- apple 0.01 0.2 0.01 ...

You can also feed in compressed version of vector file.
```
python wordsim.py -l en -v vector_file.txt.gz
```
