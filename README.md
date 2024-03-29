# CGT470-Final
This is the final project for CGT470 Data Visualization Studio course  
For final [paper](https://docs.google.com/document/d/1glUiuuX4ok9QRnM3CL8wECOl8cdism-H6adzRrq-4pc/edit)  

### Data
  * Pre-trained word embedding - GloVe: Common Crawl (840B tokens, 2.2M vocab, cased, 300d vectors) ~ about 5.25GB
  * `stanford-corenlp-full-2018-02-27` retrieved from [CoreNLP 3.9.1](https://stanfordnlp.github.io/CoreNLP/history.html)
  * `sentence.txt` is the corpus for testing sentence similarity (Feel free to add more~)
  
### Usage
  * `glove_model` will take a long time to load
  * Word similarity is able to compute after loading `glove_model`
  * `nlp = StanfordCoreNLP(r'<your-directory>\data\stanford-corenlp-full-2018-02-27')`

### Useful Links
 * Stanford CoreNLP(This this Python wrapper for CoreNLP):    [:octocat:GitHub](https://github.com/Lynten/stanford-corenlp)
 * CoreNLP demo(Demo for visualization):        [HTML](http://corenlp.run/)
 * GloVe(Word embedding AKA Word vector):               [Website](https://nlp.stanford.edu/projects/glove/)
 * GloVe paper:         [pdf](https://nlp.stanford.edu/pubs/glove.pdf)
 * The Penn Treebank:   [pdf](http://repository.upenn.edu/cgi/viewcontent.cgi?article=1246&context=cis_reports)
