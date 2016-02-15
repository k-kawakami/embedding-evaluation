# embedding-evaluation
Evaluation tool for word embeddings

## Wordsim Task
Wordsimilarity task is commonly used as a evaluation method for word-embeddings such as Word2vec, Glove.
This task investigate how your vector capture semantics between word pairs.

Wordsim task can be run on english, spanish, and french wordembeddings.

```
python wordsim.py -l en -v vector_file.txt
```

Your vector file need to satisfy the following form.
- apple 0.01 0.2 0.01 ...

You can also feed in compressed version of vector file.
```
python wordsim.py -l en -v vector_file.txt.gz
```

## Task Descriptions
- [MC-30](http://www.tandfonline.com/doi/pdf/10.1080/01690969108406936)
- [MEN-TR](http://clic.cimec.unitn.it/~elia.bruni/MEN.html)
- [MTurk-287](http://tx.technion.ac.il/~kirar/files/Radinsky-TemporalSemantics.pdf)
- [MTurk-771](http://dl.acm.org/citation.cfm?id=1963455)
- [RG-65](http://dl.acm.org/citation.cfm?id=365657)
- [RW-STANFORD](http://nlp.stanford.edu/~lmthang/data/papers/conll13_morpho.pdf)
- [WS-353-ALL](http://www.cs.technion.ac.il/~gabr/resources/data/wordsim353/)
- [WS-353-REL](http://alfonseca.org/eng/research/wordsim353.html)
- [WS-353-SIM](http://alfonseca.org/eng/research/wordsim353.html)
- [YP-130](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.214.7538&rep=rep1&type=pdf)

### Requirements
- numpy, scipy, ( gzip, prettytable )
