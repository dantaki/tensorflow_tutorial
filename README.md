# Tutorials for TensorFlow

## Table of Contents

* [Resources](#resources)
* [Setting up TensorFlow](#setting-up-tensorflow)
* [Tutorials](#tutorials)
  * [Logistic Regression](#logistic-regression)
  * [Feed-Forward Network](#feed-forward-network)
  * [2 Layer Convolutional Network](#2-layer-convolutional-network)
  * [Multilayer Convolutional Network](#multilayer-convolutional-network)

---

### Resources

* [Fundamentals of Deep Learning](http://shop.oreilly.com/product/0636920039709.do)
  * Good primer so far, however there are errata in the text and a lot of the code is deprecated
* [TensorFlow](https://www.tensorflow.org/)

### Setting Up TensorFlow

I am using Debian 9.0 and Python 2.7. Your environment may be different. Be warned :exclamation:

```
$ sudo pip install --upgrade https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-0.8.0-cp27-none-linux_x86_64.whl
$ sudo pip install python-mnist # you may or may not need this one ... 
```

The above download command fixed my issue with TensorBoard not displaying properly

### Tutorials

#### [Logistic Regression](https://github.com/dantaki/tensorflow_tutorial/blob/master/ipynb/fundamentals_of_deep_learning_companion_logistic_regression.ipynb)

#### [Feed Forward Network](https://github.com/dantaki/tensorflow_tutorial/blob/master/ipynb/fundamentals_of_deep_learning_companion_feed_forward_nextwork.ipynb)

#### [2 Layer Convolution Network](https://github.com/dantaki/tensorflow_tutorial/blob/master/ipynb/fundamentals_of_deep_learning_companion_2layer_convolutional_network.ipynb)

#### [Multilayer Convolutional Network](https://github.com/dantaki/tensorflow_tutorial/blob/master/ipynb/tensorflow_mulitlayer_convolution_network_tutorial.ipynb)


