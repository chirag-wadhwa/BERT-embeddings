# BERT embeddings using PyTorch
Generating embeddings of text from BERT uncased model

BERT uncased base model is used in this code. A random sentence is pre-processed to make it a suitable input for the model. First the text is marked with the markers [CLS] and [SEP]. This is followed by tokenizing the text. The indexed tokens thus obtained are then converted to tensors. This is then passed as input to the BERT model which generates the final embeddings. These embeddings will then later be used to fulfill the ultimate task of Video Description.
