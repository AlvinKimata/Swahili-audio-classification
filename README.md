# Swahili-audio-classification
This repository contains python scripts and notebooks for building a model to classify Swahili audio snippets.
In the first notebook submission (baseline), no preprocessing was done on the dataset, even though the use of a pretrained model (ResNet50) for performing the downstream task.
In the second notebook, the increase in model performance is attributed to use of a normalization layer from `tf.keras.layers.Normalization()` to obtain the mean and variance of pixel values in the dataset. This was done before training the model.
