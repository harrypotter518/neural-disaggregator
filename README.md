# neural-disaggregator

Implementations of NILM disaggegregators using Neural Networks, using [NILMTK](https://github.com/NILMTK/NILMTK) and Keras.

Most of the architectures are based on [Neural NILM: Deep Neural Networks Applied to Energy Disaggregation]

The implemented models are:
- Denoising autoencoder (DAE) as mentioned in [Neural NILM](https://arxiv.org/pdf/1507.06594.pdf) 
- Recurrent network with LSTM neurons as mentioned in [Neural NILM](https://arxiv.org/pdf/1507.06594.pdf) 
- Recurrent network with GRU. A variation of the LSTM network in order to compare the two types of RNNs 
- Window GRU. A variation of the GRU network in that uses a window of data as input. As described in [Sliding Window Approach for Online Energy Disaggregation Using Artificial Neural Networks](https://dl.acm.org/citation.cfm?id=3201011) by Krystalakos, Nalmpantis and Vrakas 
- Short Sequence to Point Network based on the architecture in [original paper](https://arxiv.org/abs/1612.09106)
