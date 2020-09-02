# Building-and-Deploying-Deep-Learning-Applications-with-TensorFlow

# Tensorflow

TensorFlow is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries, and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML-powered applications.

TensorFlow was originally developed by researchers and engineers working on the Google Brain team within Google's Machine Intelligence Research organization to conduct machine learning and deep neural networks research. The system is general enough to be applicable in a wide variety of other domains, as well.

TensorFlow provides stable Python and C++ APIs, as well as non-guaranteed backward compatible API for other languages.

# Install


See the TensorFlow install guide for the pip package, to enable GPU support, use a Docker container, and build from source.

To install the current release, which includes support for CUDA-enabled GPU cards (Ubuntu and Windows):

$ pip install tensorflow
A smaller CPU-only package is also available:

$ pip install tensorflow-cpu
To update TensorFlow to the latest version, add --upgrade flag to the above commands.

Nightly binaries are available for testing using the tf-nightly and tf-nightly-cpu packages on PyPi.

Try your first TensorFlow program
$ python
>>> import tensorflow as tf
>>> tf.add(1, 2).numpy()
3
>>> hello = tf.constant('Hello, TensorFlow!')
>>> hello.numpy()
b'Hello, TensorFlow!'
