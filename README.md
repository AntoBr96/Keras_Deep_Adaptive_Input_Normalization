# Keras/Tensorflow implementation of the Deep Adaptive Input Normalization layer for Time Series Forecasting

This notebook contains the Keras/Tensorflow Layer implementation of the Deep Adaptive Input Normalization model  for Time Series Forecasting proposed by Passalis *et al.* ([Deep Adaptive Input Normalization for Time series Forecasting](https://arxiv.org/pdf/1902.07892.pdf)).

The authors of the above mentioned paper propose a PyTorch implementation ([PyTorch implementation](https://github.com/passalis/dain)) of the model. A slightly reviewed version (software structure) is here reported. Results obtained by the two implementations are compared through an explicative example.

If you use the proposed Tensorflow/Keras implementation in your work please cite:

<pre>
@misc{briola_antonio_and_turiel_jeremy_david_2020_4103284,
  author       = {Briola, Antonio and Turiel, Jeremy David},
  title        = {{AntoBr96/Keras\_Deep\_Adaptive\_Input\_Normalization: 
                   Keras\_Deep\_Adaptive\_Input\_Normalization}},
  month        = oct,
  year         = 2020,
  publisher    = {Zenodo},
  version      = {v1.3},
  doi          = {10.5281/zenodo.4103284},
  url          = {https://doi.org/10.5281/zenodo.4103284}
}
</pre>

Please **always** remember to cite the original paper this work is based on:

<pre>
@article{dain,
  title={Deep Adaptive Input Normalization for Price Forecasting using Limit Order Book Data},
  author={Passalis, Nikolaos and Tefas, Anastasios and Kanniainen, Juho and Gabbouj, Moncef and Iosifidis, Alexandros},
  journal={IEEE Transactions on Neural Networks and Learning Systems},
  year={2019}
}
</pre>

### Disclaimer

The author of this notebook just implemented the Keras/Tensorflow version of a model originally defined in Passalis *et al.* ([Deep Adaptive Input Normalization for Time series Forecasting](https://arxiv.org/pdf/1902.07892.pdf)).
