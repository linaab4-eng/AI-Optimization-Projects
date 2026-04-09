# AI-Optimization-Projects
PyTorch code optimisation
# MNIST Model Optimization using Post-Training Quantization (PTQ)

This project demonstrates the application of **Post-Training Static Quantization** on a CNN model trained on the MNIST dataset using **PyTorch**. The goal is to reduce the model size and improve inference speed while maintaining high accuracy.

##  Project Overview
- **Architecture:** Custom CNN with Conv2D, MaxPool, and Dropout layers.
- **Optimization Technique:** Static Quantization (FP32 to INT8).
- **Environment:** PyTorch, Torchvision, Scikit-learn.

##  Key Results
After quantization, the model achieved:
- **Accuracy (FP32):** ~99.17%
- **Accuracy (INT8):** ~99.14%
- **Model Size Reduction:** Significant reduction in memory footprint (from ~4.8MB to ~1.2MB).
- **Inference Speed:** Faster execution on CPU-based environments.

##  How to use
1. Clone this repository.
2. Ensure you have `torch` and `torchvision` installed.
3. Run the `PTQ_Quantization_MNIST.ipynb` notebook to see the evaluation and visualization.

> [!NOTE]
> This repository currently showcases the **PTQ (Post-Training Quantization)** implementation. Scripts for **QAT** and **Pruning** are currently being refined and will be uploaded soon.
---
*Developed as part of my Master's Degree in Computer Science.*
