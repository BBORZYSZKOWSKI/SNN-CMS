# SNN-CMS
Experiments with different SNN models to solve various problems using Nengo and NxSDK frameworks.

### How to run?
>~~~~
>pip install -r requirements.txt
>~~~~

#### Spiking MNIST
 `python Nengo_MNIST_Train.py`
 
inspired by https://www.nengo.ai/nengo-loihi/examples/mnist_convnet.html

#### Optimizing Spiking MNIST
 `python Optimizing_SNNs.py`
 
inspired by https://www.nengo.ai/nengo-dl/examples/spiking-mnist.html

#### Spiking Keyword spotting task
 `python Nengo_keyword_spotting.py`
 
inspired by https://www.nengo.ai/nengo-loihi/examples/keyword_spotting.html

#### Spiking CIFAR 10 classification
 `python Nengo_cif10_conv.py`
 
inspired by https://www.nengo.ai/nengo-extras/examples/cuda_convnet/cifar10_spiking_cnn.html

#### Spiking Communication channel
 `python Nengo_communication_channel.py`
 
inspired by https://www.nengo.ai/nengo-loihi/examples/communication_channel.html

#### Nengo Fashion MNIST
Inserting a Tensorflow / Keras network into the Nengo framework.

`python Nengo_fashion_mnist.py`
 
inspired by https://www.nengo.ai/nengo-dl/v2.2.0/examples/tensorflow-models.html


### Useful links

* [hls4ML](https://hls-fpga-machine-learning.github.io/hls4ml/) - Firmware implementations of machine learning algorithms using high level synthesis language (HLS)
* [Loihi chip overview](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8259423) - Loihi: A Neuromorphic
Manycore Processor with
On-Chip Learning
* [Frontiers in neuroscience - article](https://www.frontiersin.org/articles/10.3389/fnins.2018.00774/full) - Deep Learning With Spiking Neurons: Opportunities and Challenges
