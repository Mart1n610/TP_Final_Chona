# Face Emotion Classifier

This project contains a Convolutional Neural Network (CNN) that classifies faces into three categories: Happy, Sad, and Angry.

## Project Structure

- `CNN.ipynb`: This Jupyter notebook contains the code for training the CNN.
- `Consigna.md`: This markdown file contains the project requirements.
- `data/`: This directory contains the images used for training the CNN. It is divided into three subdirectories, one for each emotion: Happy, Sad, and Angry.
- `face_emotion_classifier.h5`: This is the trained model, saved in HDF5 format.
- `graph`: This file contains a visualization of the model architecture.

## How to Run

1. Install the required Python packages. You can do this by running `pip install -r requirements.txt` (you'll need to create this file with your project's dependencies).
2. Open the `CNN.ipynb` notebook in Jupyter and run the cells to train the model.
3. The trained model will be saved as `face_emotion_classifier.h5`.

## Model Usage

You can load the trained model using Keras:

```python
from tensorflow.keras.models import load_model

model = load_model('face_emotion_classifier.h5')