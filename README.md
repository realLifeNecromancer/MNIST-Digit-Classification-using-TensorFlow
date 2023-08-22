# MNIST Digit Classification using TensorFlow

This repository contains code for a simple digit classification task using TensorFlow. The goal is to classify handwritten digits from the MNIST dataset.

## Introduction

This code demonstrates the process of building and training a neural network to classify handwritten digits from the famous MNIST dataset. The MNIST dataset consists of a collection of grayscale images of hand-drawn digits (0 to 9) and their corresponding labels.

## Getting Started

To use this code, you'll need to have Python and TensorFlow installed on your system. You can install TensorFlow using the following command:

```bash
pip install tensorflow
```

Clone this repository to your local machine:

```bash
git clone https://github.com/realLifeNecromancer/MNIST-Digit-Classification-using-TensorFlow.git
```

## Usage

1. Navigate to the project directory:

```bash
cd mnist-digit-classification
```

2. Open the Python script `mnist_classification.py` in your preferred code editor.

3. Run the script:

```bash
python mnist_classification.py
```

## Model Architectures Explored

### Single Output Layer Model

The initial model architecture consists of a single output layer with 10 units, corresponding to the digits 0 through 9. The input data is flattened to a 1D array of size 784 before being fed into the model.

### Model with Hidden Layer

An alternative model architecture is explored, featuring a hidden layer with 100 ReLU (Rectified Linear Unit) activation units. The output layer retains the 10 units for classification. This architecture is designed to capture more complex relationships within the data.

## Results

The code provides a way to evaluate the classification accuracy of the trained models on the MNIST test dataset. Additionally, it generates confusion matrices to visualize the performance of the models.

### Single Output Layer Model

- Classification Accuracy: 92.43
- Confusion Matrix:
![confusion matrix single](https://github.com/realLifeNecromancer/MNIST-Digit-Classification-using-TensorFlow/assets/108059668/f9e53468-889b-40b9-a3a1-c6d39da3517e)

### Model with Hidden Layer

- Classification Accuracy: 95.72
- Confusion Matrix:
![Model with Hidden Layer](https://github.com/realLifeNecromancer/MNIST-Digit-Classification-using-TensorFlow/assets/108059668/61f831c9-c551-4c8c-a2bc-54d5b470aedb)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
