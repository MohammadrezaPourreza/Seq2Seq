# Seq2Seq

This repository contains sequence to sequence models with LSTM and GRU. In this repository, I implemented two separate models first one is without attention, and the other one has an attention layer. Each model is enabled to work either with GRU or LSTM, plus, it is also possible to use it both bidirectional and multilayer. For using LSTM or GRU you should uncomment the specific parts that are defined by #LSTM and #GRU in the code. 
For our specific task, we have a dataset containing a description and some keywords that are chosen based on the descriptions. Due to the lack of data, I also used data augmentation using the Nlpaug package.
