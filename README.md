# POS Tagging 
Using Bi- and Tri-Gram Viterbi algorithm to tag a sequence of words

### Run the Program 
Put the three files: corpus.py, viterbi.py and test.py into one directory and in that directory, run:
```
python test.py [bi or tri] [path to the the training file] [path to the testing file]
```
where you need to supplement:
* Mode - "bi" or "tri" for testing whether bigram or trigram
* Path to the training file
* Path to the testing file
For example you can run this command to test a trigram tagger:
```
python test.py tri /home/twt.train.json /home/twt.test.json
```
