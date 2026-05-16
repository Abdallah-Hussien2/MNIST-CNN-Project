# Handwritten Digit Recognition using CNN (MNIST)

This project implements a Convolutional Neural Network (CNN) using PyTorch for handwritten digit recognition on the MNIST dataset.
Two different optimizers were tested and compared:

- Adam Optimizer
- SGD Optimizer

---

## Project Features

- Data preprocessing and normalization
- Training and validation process
- Performance evaluation using accuracy and loss
- Visualization of training and validation results
- Comparison between Adam and SGD optimizers

---

## Dataset

MNIST Dataset:  
https://pytorch.org/vision/stable/generated/torchvision.datasets.MNIST.html

---

## Results

| Model | Accuracy | Loss |
|-------|----------|------|
| Adam | 99.12% | 0.0359 |
| SGD | 99.13% | 0.0253 |

---

## How to Run

1. Open the notebook in Google Colab
2. Run all cells sequentially
3. The model will train automatically
4. Training and validation graphs will be displayed
5. Final results and comparison table will appear at the end

---

## Technologies Used

- Python
- PyTorch
- Torchvision
- Matplotlib
- Pandas
