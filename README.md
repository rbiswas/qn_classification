# Question type classification


Multi class classifier is built using Bidirectional LSTM.

Loss function used: categorical_crossentropy

I have used Pretrained word embedding(GLoVe).

Dependent Packages:
* python >= 2.7
* keras = 2.0.8
* tensorflow = 1.1.0
* numpy = 1.13.1
* pandas = 0.20.2
* sklearn = 0.18.1
* argparse
* re
* json
* random
* pickle


Download GLoVe pretrained model (glove.42B.300d.txt) from below link.

http://nlp.stanford.edu/data/glove.42B.300d.zip

Change path of input file and GLoVe file path in Config.json

#To train

python train.py

#To test

python test.py -q "Is it working fine?"
