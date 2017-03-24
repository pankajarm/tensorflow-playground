# Tensorflow Playground

This is the playground for basics but some of most important tensorflow tutorials and nano projects, all coded with care...

1. [Linear Regression with sample data](https://github.com/pankymathur/tensorflow-playground/blob/master/tensorflow-linear-regression.ipynb)
2. [Logistic Regression with MNIST]()
3. [Neural Network with MNIST]()
4. Convutional Neural Network (Upcoming..)

### Install
I am using [Conda](https://www.continuum.io/anaconda-overview) to install TensorFlow. You might already have a TensorFlow environment, but please check below to make sure you have all the necessary packages. If you have never used Conda environments before, please go through my other tutorial [What is Anaconda and Why should I bother about it?](http://pankajmathur.com/what-is-anaconda-and-why-should-i-bother-about-it/)

Assuming you have conda install on your machine, plesae run the following commands to have tensorflow-playground ready for you to play.

### OS X or Linux
Run the following commands to setup your environment:

```
conda create -n tensorflow-playground python=3.5
source activate tensorflow-playground
conda install pandas matplotlib jupyter notebook scipy scikit-learn
pip install tensorflow
```

### Windows
And installing on Windows. In your console or Anaconda shell:

```
conda create -n tensorflow-playground python=3.5
activate tensorflow-playground
conda install pandas matplotlib jupyter notebook scipy scikit-learn
pip install tensorflow
```
