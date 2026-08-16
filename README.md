# Handwritten Digit Classification using CNN

A **Computer Vision** project that uses a Convolutional Neural Network (CNN) built with **Keras** to classify handwritten digits from the **MNIST dataset**.

## Features

* Uses the MNIST handwritten digit dataset
* Image normalization and reshaping
* CNN architecture with convolution and max-pooling layers
* Dense layers for digit classification
* Trained for 5 epochs
* Evaluates model performance on test data

## Technologies Used

* Python
* Keras / TensorFlow
* NumPy
* MNIST Dataset

## Model Architecture

* Conv2D (32 filters)
* MaxPooling2D
* Conv2D (64 filters)
* MaxPooling2D
* Conv2D (64 filters)
* Flatten
* Dense (64 neurons)
* Dense (10 neurons with Softmax)

## Output

The trained model predicts one of the **10 handwritten digit classes (0–9)** and reports the test **loss and accuracy**.

## How to Run

Install the required dependencies:

```bash
pip install -r requirements.txt
```

Then run the Python script:

```bash
python ImageClassification_CNN_MNIST.ipynb
```

## Project Type

**Computer Vision | Deep Learning | Image Classification**
