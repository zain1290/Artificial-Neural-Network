# Artificial Neural Network

An implementation of a feedforward Artificial Neural Network (ANN) built from scratch in Python, applied to a multi-class classification problem.

---

## Problem Description

A supervised classification task where the network learns to categorize inputs into one of **7 classes** given **10
input features**. The assignment also explorn logical functions (AND, OR, XOR) todemonstrate the need for multi-layer architectures.

---

## Network Architecture

| Layer | Size | Activation |
|-------|------|------------|
| Input | 10 | — |
| Hidden | 16 | ReLU |
| Output | 7 | Softmax |

- Loss function: Softmax Cross-Entropy
- Optimizer: Gradient descent (configurable
- Regularization: Early stopping with patience

---

## Implementation Details

Built entirely from scratch (no deep learning frameworks) with the following components:

- **Linear layers** with configurable weight initialization
- **Activation functions**: ReLU, Sigmoid, S
- **Loss functions**: SoftmaxCrossEntropy, BinaryCrossEntropy
- **Backpropagation** with full-batch and mi

**Weight initialization strategies tested:**

---

## Dataset

| File | Description |
|------|-------------|
| `features.txt` | 10 input features per sam
| `targets.txt` | Class labels (7 classes) |
| `unknown.txt` | Unlabeled test samples for

Data split: **70% train / 15% validation / 1lization applied to features.

---

## Repository Structure

├── src/   
│   ├── FINAL.ipynb          # Main submission notebook   
│   ├── Main.ipynb           # Development n   
│   ├── Toolbox.ipynb        # Shared utility functions   
│   ├── Zain.ipynb           # Individual me   
│   ├── Danny.ipynb   
│   ├── Deyan.ipynb   
│   ├── Drago.ipynb   
│   └── Group_00_classes.txt # Class definit   
├── data/    
│   ├── features.txt   
│   ├── targets.txt   
│   └── unknown.txt   
└── CI___Assignment_2___ANN__2024_2025_.pdf   # Assignment specification   

---

## Setup

```bash
uv sync
jupyter notebook src/FINAL.ipynb

```
