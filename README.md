# n_grams

A current notebook calculates the probability of a word based on words before it.
The current bigram model creates a dictionary of dictionaries where the key, word a, calls a dictionary of where that key, word b, calls the probability.

dict[word_a][word_b] = probability
