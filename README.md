# Purpose of This Repo

This repository contains all hands-on materials for the **Introduction to Deep Learning** course: demos, exercises, solutions, and a final project. Learn to build, train, and evaluate neural networks using PyTorch.

---

## Table of Contents

- [Course Structure](#-course-structure)
- [Repository Structure](#️-repository-structure)
- [Getting Started](#-getting-started)
- [What You'll Learn](#what-youll-learn)
- [Resources](#-resources)
- [License](#-license)

---

## Course Structure

The course is organized into a progressive learning path designed to take you from neural network fundamentals to building complete deep learning systems. The course progresses through **10 skill pairs**, each with:

- **Demo notebooks**: Instructor-led walkthroughs
- **Exercise notebooks**: Student practice with guided TODOs  
- **Solution notebooks**: Reference implementations (prefixed with `_SOLUTION-`)

**Tip**: Exercise TODOs include hints that guide without revealing answers.

### Learning Path

For each skill pair:
1. **Watch demo** → 2. **Complete exercise** → 3. **Check solution** 

Once you've completed the course: → 4. **Build project**

#### Skill Pairs

| # | Topic | Key Focus |
|---|-------|-----------|
| **1** | **Perceptron** | Single-layer networks, linear boundaries |
| **2** | **Activation Functions** | Non-linearity, sigmoid/tanh/ReLU comparison |
| **3** | **Multi-Layer Perceptron** | Stacking layers, solving XOR |
| **4** | **Forward Pass & Tensors** | Data flow, shape transformations |
| **5** | **Loss Functions** | MSE, cross-entropy, task-appropriate losses |
| **6** | **Training Loop** | Gradient descent, backpropagation, SGD vs Adam |
| **7** | **Data Preprocessing** | Train/val/test splits, normalization, DataLoaders |
| **8** | **Overfitting vs Underfitting** | Bias-variance tradeoff, loss curve diagnosis |
| **9** | **Evaluation Metrics** | Accuracy, precision, recall, F1, regression metrics |
| **10** | **Model Improvement** | Hyperparameter tuning, dropout, regularization |

Each skill pair builds on the previous one, ensuring you develop a solid foundation before moving to more advanced concepts.

#### Final Project

The course culminates in a hands-on project that brings together everything you've learned.

Build a complete diabetes prediction classifier:
- Load and preprocess medical data
- Design MLP architecture  
- Train with proper validation
- Evaluate with multiple metrics

See `project/README.md` for instructions.

---

## Repository Structure

The repository is organized by skill pair (+ final project), with each folder containing everything you need for that topic.

```
cd1818-intro-to-deep-learning/
├── 1-perceptron/                   # Demos, exercises, solutions for Skill Pair 1
├── 2-activations/                  # Skill Pair 2 materials
├── 3-mlp/                          # Skill Pair 3 materials
├── 4-feedforward/                  # Skill Pair 4 materials
├── 5-loss/                         # Skill Pair 5 materials
├── 6-training/                     # Skill Pair 6 materials
├── 7-preprocessing/                # Skill Pair 7 materials
├── 8-overfitting-underfitting/     # Skill Pair 8 materials
├── 9-evaluation/                   # Skill Pair 9 materials
├── 10-improvements/                # Skill Pair 10 materials
├── project/                        # Final course project
│   ├── starter-kit/                # Student starting point
│   ├── solution/                   # Reference implementation
│   └── README.md
└── README.md
```

Each skill pair folder contains `demo`, `exercise`, and `_SOLUTION-exercise` notebooks, plus an `assets/` folder for generated visualizations.

---

## Getting Started

Follow these steps to set up your environment and begin working through the course materials:

```bash
# Clone repository
git clone <repository-url>
cd cd1818-intro-to-deep-learning

# Install dependencies
pip install torch torchvision numpy matplotlib pandas scikit-learn datasets jupyter

# Launch Jupyter
jupyter notebook
```

With your environment ready, you can now start with Skill Pair 1 and work your way through the course sequentially.

---

## What You'll Learn

By the end of this course, you'll have mastered the core skills needed to build and train neural networks.

By completing this course, you'll be able to:

- [x]  Build neural networks from scratch in PyTorch  
- [x]  Implement complete training loops with gradient descent  
- [x]  Select appropriate loss functions and optimizers  
- [x]  Preprocess data and create efficient DataLoaders  
- [x]  Diagnose overfitting/underfitting from loss curves  
- [x]  Evaluate models with task-appropriate metrics  
- [x]  Tune hyperparameters and apply regularization

These skills form the foundation for working with any deep learning architecture or framework.

---

## Resources

- [PyTorch Documentation](https://pytorch.org/docs/stable/index.html)
- [PyTorch Tutorials](https://pytorch.org/tutorials/)

---

## License

See `LICENSE.md` for details.

---

> **Happy Learning! 🚀**
