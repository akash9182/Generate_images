## Overview

This is the code for [this](https://youtu.be/3-UDwk1U77s) video on Youtube by Siraj Raval as part of the Udacity Deep Learning Nanodegree. We're using a [variational autoencoder](https://jaan.io/what-is-variational-autoencoder-vae-tutorial/) to generate novel digit images after training on the [MNIST](http://yann.lecun.com/exdb/mnist/) dataset. We use Keras in this repository so the code is relatively simple, for a more in depth look (at say, reparameterization check [this](https://github.com/EderSantana/gumbel) repo).

## Dependencies

* numpy
* keras
* scipy
* matplotlib

Install dependencies using [pip](https://pip.pypa.io/en/stable/).

## Usage

Run `jupyter notebook` in terminal and the code will pop up in your browser. Install it [here](http://jupyter.readthedocs.io/en/latest/install.html) if you don't have it.

## Credits

Credits go to the [creator](https://github.com/fchollet/keras/blob/master/examples/variational_autoencoder.py) of Keras. I've merely created a wrapper to get people started.
