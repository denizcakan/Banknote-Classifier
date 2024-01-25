# Turkish Banknote Classifier

Turkish Banknote Classifier is a simple, efficient, and user-friendly tool designed to classify Turkish banknotes. Various neural networks, optimization types and activation functions were tried and you can see the results in the jpynb file.

## Prerequisites

All you need to run is described in the jpynb file. They are also shared below:

```bash
pip install tensorflow
pip install scikit-learn
```

Import part:

```python
import cv2
import os
import tensorflow as tf
import numpy as np
import matplotlib.pyplot as plt
from tensorflow.keras import models, layers, optimizers
from sklearn.model_selection import train_test_split
```

## Dataset

The dataset consists of 6 folders. Each folder contains photos of that banknote type. There are approximately 1000 photographs of each type, 6000 photographs in total. There is also a link to the dataset [here](https://www.kaggle.com/datasets/baltacifatih/turkish-lira-banknote-dataset).



