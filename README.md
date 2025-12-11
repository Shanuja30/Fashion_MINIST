# Fashion Item Classifier

## Project Overview
Fashion Item Classifier is a web application built using **Streamlit** that classifies images of fashion items into 10 categories. The classification is powered by a **Convolutional Neural Network (CNN)** trained on the **Fashion MNIST dataset** using **TensorFlow Keras**. Users can upload an image of a fashion item, and the app predicts its category with high accuracy.

## Features
- Upload images of fashion items in `jpg`, `jpeg`, or `png` formats.
- Preprocess images for model prediction (resizing, grayscale conversion, and normalization).
- Classify fashion items into 10 categories:
  - T-shirt/top
  - Trouser
  - Pullover
  - Dress
  - Coat
  - Sandal
  - Shirt
  - Sneaker
  - Bag
  - Ankle boot
- Display the uploaded image alongside the predicted category in a user-friendly interface.

## Technologies Used
- **Streamlit** – Web framework for building the interactive app.
- **TensorFlow Keras** – Deep learning framework for building and training the CNN model.
- **NumPy** – For numerical operations and image array manipulation.
