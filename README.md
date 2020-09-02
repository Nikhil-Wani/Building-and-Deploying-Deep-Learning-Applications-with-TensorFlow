# Building-and-Deploying-Deep-Learning-Applications-with-TensorFlow

# Topics include:

1. What's TensorFlow?
2. Hardware, software, and language requirements
3. Creating a TensorFlow model
4. Training a deep learning model with TensorFlow
5. Visualizing the computational graph
6. Adding custom visualizations to TensorBoard
7. Exporting models for use with Google Cloud


# What's Tensorflow

TensorFlow is an end-to-end open source platform for machine learning. It has a comprehensive, flexible ecosystem of tools, libraries, and community resources that lets researchers push the state-of-the-art in ML and developers easily build and deploy ML-powered applications.

TensorFlow was originally developed by researchers and engineers working on the Google Brain team within Google's Machine Intelligence Research organization to conduct machine learning and deep neural networks research. The system is general enough to be applicable in a wide variety of other domains, as well.

TensorFlow provides stable Python and C++ APIs, as well as non-guaranteed backward compatible API for other languages.

<b>Requirements</b>

1. numpy:

NumPy is a python library used for working with arrays. It also has functions for working in domain of linear algebra, fourier transform, and matrices. NumPy was created in 2005 by Travis Oliphant. It is an open source project and you can use it freely. NumPy stands for Numerical Python.

$ pip install numpy
  
2. pip>=9.0.0

PIP is a package manager for Python packages, or modules if you like.

Install PIP
If you do not have PIP installed, you can download and install it from this page: https://pypi.org/project/pip/

3. Keras

Keras is a minimalist Python library for deep learning that can run on top of Theano or TensorFlow. It was developed to make implementing deep learning models as fast and easy as possible for research and development

$ pip install Keras

4. pandas

In computer programming, pandas is a software library written for the Python programming language for data manipulation and analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series

$ pip install pandas

5. scikit-learn

Scikit-learn is a free machine learning library for Python. It features various algorithms like support vector machine, random forests, and k-neighbours, and it also supports Python numerical and scientific libraries like NumPy and SciPy.

$ pip install sklearn

6. scipy

SciPy is a library that uses NumPy for more mathematical functions. SciPy uses NumPy arrays as the basic data structure, and comes with modules for various commonly used tasks in scientific programming, including linear algebra, integration (calculus), ordinary differential equation solving, and signal processing.

$ pip install scipy

7. tensorflow>=1.0.0

See the TensorFlow install guide for the pip package, to enable GPU support, use a Docker container, and build from source.

To install the current release, which includes support for CUDA-enabled GPU cards (Ubuntu and Windows):

$ pip install tensorflow

A smaller CPU-only package is also available:

$ pip install tensorflow-cpu

To update TensorFlow to the latest version, add --upgrade flag to the above commands.

8. google-api-python-client

This is the Python client library for Google's discovery based APIs. 

pip install virtualenv

<p>virtualenv <your-env></p>
  
<p><your-env>\Scripts\activate</p>
  
<p><your-env>\Scripts\pip.exe install google-api-python-client</p>


