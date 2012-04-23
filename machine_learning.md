# Practical Machine Learning
## Andrew Cantino & Ryan Stout

### Andrew Cantino:

Machine learning _predicts_ data based on data: "classification".

Decision tree learning: Basically a flow chart, built automatically from a
corpus. Each node should be what best divides the corpus.

"feature": unit to consider when classifying data.

Support Vector Machines (SMVs): Map features to a graph, draw a line that
maximizes the space between two groups of features. Plot new data, check against
line.

Naive Bayes: Basically just word counting. Really effective on text or other
things that have a lot of features.

Neural Nets: Really complex; hidden layers are hard to interpret. Try SMVs
first.

The Curse of Dimensionality: The more features you have, the more data you need
in your corpus. Roughly exponential.

"Overfitting": You don't want the algorithm to *memorize*, but to *generalize*
about the data. Test on different data than you train on.


### Ryan Stout:

"bag of words": ignores sentence structure, etc. Just what words are in the
data. Create a dictionary. Usually, just keep the top X number (like 10,000).

Improve:
* Bigger dictionary
* Bi/Trigrams
* Tag parts of speech and treat them differently
* moar data
