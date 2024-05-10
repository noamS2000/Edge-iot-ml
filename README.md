# Edge-iot-ml
This repository contains Jupyter notebooks that guide you through the entire process of training a classification model for anomaly detection on an edge-based Internet of Things (IoT) dataset. The model is designed to classify packets captured by edge devices as either containing an attack or normal activity.

# Type of challenge
- Binary classification
- Multiclass classification

# Notebooks
1. **data exploring** - Overview of the dataset, exploring the data and the non-numerical data in more depth.
2. **pipelining** - Creating a full pipeline to modify the data and prepare it for training different kinds of models. In this notebook i transform columns to numbers, create one-hot-arrays and groups
3. **statiscal analysis** - Before training models, I created a notebook that contains an overview of the now-modified dataset (correlations, feature improtances, dimentionality reduction, etc...)
4. **RandomForest_PCA** - Training and thoroughly evaluating RandomForest model with and without the use of PCA algortithm
5. **Unsupervised** - Using differnet unsupervised ML models for the classification challenge
6. **DNN** - Training a DNN model, and fine tunning it with RandomSearch and other methods
