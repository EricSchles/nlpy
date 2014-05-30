#nlpy -  A natural language processing library written in python


nlpy.ngram:

A simple Ngram analyzer.

Methods:

ngrams(n): n is an integer.

Returns the ngram for the initialized string.

uni_gram(): 

Returns the unigram for a given initialized string.

bi_gram():

Returns the bigram for a given initialized string.

tri_gram():

Returns the trigram for a given initialized string.

comparison(other_ngram_object):

Takes in an Ngram object and compares it against the initialized Ngram object.


##Examples:

from nlpy import ngram.Ngram

x = Ngram("Hello there sally")
y = Ngram("How are you sally?")

x.comparison(y)

x.ngrams(5)

x.uni_gram()
x.bi_gram()
x.tri_gram()