# seq2seq-models
Some different seq2seq models, based on the Spell-Checker project.

# One hot encoding
Often one hot encoding is used in these models. Especially with small sets of symbols, like characters.

# Embedding
If an embedding layer is used, no one hot encoding is used for the embedded symbols. This does not mean that no one hot encoding is used at all, because the output of the model may very well still be one hot encoded, especially if softmax is used.
