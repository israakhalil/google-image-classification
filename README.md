# Google Image Classification
Google Image Classification Xception Model

The images belong typically to 4 classes:

* Art & Culture
* Architecture
* Food and Drinks
* Travel and Adventure

# Xception Model
Xception Model is proposed by Francois Chollet. Xception is an extension of the inception Architecture which replaces the standard Inception modules with depthwise Separable Convolutions.

# Tech stack
Python · TensorFlow / Keras · Xception (transfer learning) · Jupyter

# Pipeline
1. Load the image dataset into training, validation and test sets (224×224, batch size 50)
2. Data augmentation and preprocessing layers
3. Load the pre-trained Xception base model and add a classification head
4. Train and evaluate on the test set
5. Save / load the model and predict on new images

# Usage
Open [`google-image-classification-xception-model.ipynb`](google-image-classification-xception-model.ipynb) in Jupyter, Kaggle or Google Colab and set the data directory paths to your copy of the dataset.

# License
MIT
