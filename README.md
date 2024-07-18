Given data:  We have provided you with a dictionary of N = 5167 words. Each word in the
dictionary is written using only lower-case Latin characters i.e. a - z. At test time,we
will need to guess each word from the dictionary given its (deduplicated, sorted and truncated)
bigram list

To Do: develop an ML algorithm (we recommend a decision tree but other
solutions are admissible as well) that can play this guessing game on words from the given
dictionary

NOTE: Your code must implement a my_fit() method that
takes a dictionary as a list of words and returns a trained ML model. Your code must also
implement a my_predict() method that takes your learnt model and a tuple of bigrams
sorted in ascending order, and returns a list of guesses. The my_predict() must return a
list even if it is making only a single guess. If the list contains more than 5 guesses, only
the first 5 will be considered

