# Deep-Learning-Assignment-Neil
RNN and CNN notebook
This repository contains two Google Colab notebooks developed for a Deep Learning assignment.
Both notebooks load their datasets directly from Google Drive using:

from google.colab import drive
drive.mount('/content/drive')

1️⃣ CNN Notebook

File: CNN.ipynb

Implements a Convolutional Neural Network for satellite image classification.

Dataset is stored in Google Drive with the structure:

Satellite_Image_Classification_Neil/data/
    ├── cloudy/
    ├── desert/
    ├── green_area/
    └── water/


Includes preprocessing, model training, evaluation, and saving the trained model.

2️⃣ RNN Notebook

File: RNN.ipynb

Implements an LSTM-based Recurrent Neural Network for Twitter sentiment analysis.

Dataset is loaded from:

Twitter_US_Airline_Sentiment/tweets.csv


Includes text preprocessing, tokenization, model building, training, and evaluation.

Dataset Note

Datasets are not included in this repository due to size limitations.
Ensure they are stored in Google Drive before running the notebooks.
