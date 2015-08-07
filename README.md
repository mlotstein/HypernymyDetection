# HypernymyDetection
Tests a novel form of post-processing designed to improve hypernymy detection in unsupervised, vector-based distributional lexical semantic models.

In most state-of-the-art models of this sort, positive instances of hypernymy (consisting of a hyponym, like dog<sub>1</sub>*, and a hypernym like animal<sub>1</sub>) are recognized by the extent to which the features of the sparse vector representing the hyponym are also members of the set of features of the sparse vector representing the hypernym. Unfortunately, as per analysis in my thesis, the tendency for these sparse feature vectors to share very few features undermines the effectiveness of these models.

This code (1) builds two conventional sparse vector-spaces representing the meanings of words in a corpus and (2) performs additional post-processing on those representations, resulting in new, modified vector-spaces.
