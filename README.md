# deep-neural-network-from-scratch
This project implements a **Deep Neural Network from scratch using NumPy**, without relying on high-level deep learning frameworks such as TensorFlow or PyTorch.  
The model is applied to a **binary image classification task (Cat vs Non-Cat)**.

The project is divided into two parts:
1. Core neural network implementation
2. Application to image classification

---

## Project Objectives

* Implement a deep neural network from first principles
* Manually code forward and backward propagation
* Train a neural network using gradient descent
* Apply the model to a real image classification task
* Compare shallow and deep neural network performance

---

## Model Architecture

* Two-layer Neural Network  
  LINEAR → RELU → LINEAR → SIGMOID

* L-layer Deep Neural Network  
  [LINEAR → RELU] × (L−1) → LINEAR → SIGMOID

---

## Dataset

* Binary image classification dataset (Cat vs Non-Cat)
* Images stored in HDF5 format
* Each image has shape `(num_px, num_px, 3)`

---

## Implementation Details

* Language: Python
* Libraries: NumPy, Matplotlib, h5py
* No deep learning frameworks used
* Fully vectorized implementation

---

## Results

* The deep L-layer model achieves higher accuracy than the two-layer model
* Demonstrates the benefit of increased network depth
* Cost decreases consistently during training

---


