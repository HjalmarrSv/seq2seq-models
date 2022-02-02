# seq2seq-models
Some different seq2seq models, based on the Spell-Checker project.

# One hot encoding
Often one hot encoding is used in these models. Especially with small sets of symbols, like characters. See: seq2seqTF2.x.ipynb.

# Embedding
If an embedding layer is used, no one hot encoding is used for the embedded symbols. This does not mean that no one hot encoding is used at all, because the output of the model may very well still be one hot encoded, especially if softmax is used. See: seq2seqTF2.x_embedding.

# Mixed Precision
Mixed precision may not work for Tensorflow less than 2.7. It seems LSTM is not compatible with Mixed precision until at that version. You can easily add the needed code to any version here. Limited functionality may be found in earlier versions, see:

# Get and set weights
The functional model is flexible. You can copy layers with their weights to a new model (see previous models), or build a new model and get the weights from another model, see: 

