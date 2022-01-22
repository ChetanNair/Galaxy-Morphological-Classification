# Galaxy Morphology Classification

## Overview
This project looks at classifying galaxies morphologically from their images. 

# Getting Started
## Dependencies
keras, numpy, pandas

## Dataset
https://data.galaxyzoo.org

## Detailed Explanation
The keras framework for Python has been used to create and train a convolutional neural network for the purpose of classification. Tensorflow's tensoboard was used to log and view analytics while training the model. The DataPrep notebook documents the process of preparing the data for training and testing. Numpy, and pandas are used for this data processing. Each galaxy image is processed into smaller images so that model training becomes less expensive. This is described in more detail within the notebook.
The CNN model is defined using keras in the ModelFitting notebook. It is also trained within the same notebook.

## Author
Chetan Nair - chetan.r.nair@gmail.com
