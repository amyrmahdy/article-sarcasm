# **Sarcasm Detection**

This is a project to detect sarcasm in news headlines using natural language processing (NLP) and machine learning (ML) techniques. The dataset used in this project is the [News Headlines Dataset](https://www.kaggle.com/datasets/rmisra/news-headlines-dataset-for-sarcasm-detection) for Sarcasm Detection from Kaggle.

## **Prerequisites**

- Python 3.x

- Jupyter Notebook

- Pandas

- NumPy

- TensorFlow

- Keras

- Matplotlib

- scikit-learn



## **Getting Started**

1. Clone this repository to your local machine.

2. Download the dataset from Kaggle and extract it into the data folder.

3. Open the sarcasm_detection.ipynb notebook in Jupyter Notebook.

4. Run the cells in the notebook to train and evaluate the models.


## **SNN Model**

The SNN model consists of an input layer, two hidden layers with 100 neurons each, and an output layer. The input sequences are padded to a maximum length of 152 and a vocabulary size of 30000 is used. The model is trained for 100 epochs and uses binary crossentropy as a loss function and accuracy as a metric.

The SNN model achieved an f1-score of 0.55 and a confusion matrix is plotted to visualize the performance of the model.

![snn plot](snn.png) 

## **CMP Model**

The CMP model consists of an input layer with an embedding layer, a convolutional layer, a max-pooling layer, a dropout layer, a flatten layer, two dense layers with 10 and 1 neurons respectively. The model is trained for 100 epochs and uses binary crossentropy as a loss function and accuracy as a metric.

The CMP model achieved an f1-score of 0.84, which is a significant improvement over the SNN model. A confusion matrix is also plotted to visualize the performance of the model.

![cnn plot](cnn.png) 


## **Improvement**

The CMP model achieved better accuracy compared to the SNN model. However, there is still room for improvement. One possible approach is to use pre-trained word embeddings such as Word2Vec or GloVe to capture better semantic features.

## **Contributions**


If you are interested in contributing to this project, I welcome your contributions! Feel free to fork the repository and submit pull requests with your changes.

## **License**

This dataset is released under the MIT License. Feel free to use it for any purpose, commercial or non-commercial. If you use this dataset, we would appreciate it if you could provide a link back to this repository.

<br >
<br >

**Author: amyrmahdy**

**Date: 14 Jan 2023**



