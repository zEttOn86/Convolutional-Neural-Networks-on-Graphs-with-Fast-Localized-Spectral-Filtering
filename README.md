# Chainer Graph CNN

This is a Chainer implementation of
[_Defferrard et al., "Convolutional Neural Networks on Graphs with Fast Localized Spectral Filtering", NIPS 2016._](https://arxiv.org/abs/1606.09375)

Use it at your own risk.
See [license](LICENSE) for details.

This is not the original author's implementation. This implementation was based on [https://github.com/mdeff/cnn_graph](https://github.com/mdeff/cnn_graph).

### Note

I updated [original repository](https://github.com/pfnet-research/chainer-graph-cnn) to work on chainer v5.

Usage
-----
```
# Trains a GraphCNN on MNIST
$ python tools/train.py -c configs/default.json -o results -e 100 -g 0
```

Prerequisites
-------------
```
python 3.5.5
chainer (5.1.0)
cupy (5.1.0)
nose (1.3.7)
scikit-learn (0.19.2)
scipy (1.1.0)
```

Results
-------


License
-------
MIT License. Please see the LICENSE file for details.
