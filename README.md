# Keras/Tensorflow implementation of the Deep Adaptive Input Normalization layer for Time Series Forecasting

This notebook contains the Keras/Tensorflow Layer implementation of the Deep Adaptive Input Normalization model  for Time Series Forecasting proposed by Passalis *et al.* ([Deep Adaptive Input Normalization for Time series Forecasting](https://arxiv.org/pdf/1902.07892.pdf)).

The authors of the above mentioned paper propose a PyTorch implementation ([PyTorch implementation](https://github.com/passalis/dain)) of the model. A slightly reviewed version (software structure) is here reported. Results obtained by the two implementations are compared through an explicative example.

If you use this code in your work please cite the following paper:

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
