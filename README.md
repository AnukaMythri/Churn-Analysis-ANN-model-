# Churn Analysis-ANN Model

### Overview

In this project, we begin by exploring and visualizing the data. Also, we will build a **Customer Churn Prediction Model** using artificial neural network.

Customer churn measures how and why are customers leaving the business. We will use telecom customer churn dataset from kaggle (link below) and build a deep learning model for churn prediction. We will also understand precision,recalll and accuracy of this model by using confusion matrix and classification report

### PROJECT AIM

To understand and measure how and why customers are leaving the business.

### TECHNOLOGIES USED

- The Code is written in Python 3.6.9 using google colaboratory. You can go to this [link](https://colab.research.google.com/notebooks/intro.ipynb).
- You can also use Jupyter Notebook. Touse JupyterNotebook,
First, download [Anaconda](https://www.anaconda.com/download). By downloading Anaconda, you get conda, Python, Jupyter Notebook and hundreds of other open source packages.
Now, to install Tensor flow and keras, follow steps below,

```pythonscript
# install pip in the virtual environment
$ conda install pip
# install Tensorflow CPU version
$ pip install --upgrade tensorflow # for python 2.7
$ pip3 install --upgrade tensorflow # for python 3.*
# install Keras (Note: please install TensorFlow first)
$ pip install Keras
```
### PYTHON LIBRARIES USED
```pythonscript
import pandas as pd
from matplotlib import pyplot as plt
import seaborn as sns
import tensorflow as tf
from tensorflow import keras
```

### DATASET INFO
- Dataset is downloaded from Kaggle: https://www.kaggle.com/blastchar/telco-customer-churn
- The data set includes information about:
  - Customers who left within the last month – the column is called Churn
  - Services that each customer has signed up for – phone, multiple lines, internet, online security, online backup, device protection, tech support, and streaming TV and movies
  - Customer account information – how long they’ve been a customer, contract, payment method, paperless billing, monthly charges, and total charges
  - Demographic info about customers – gender, age range, and if they have partners and dependents
  
  
