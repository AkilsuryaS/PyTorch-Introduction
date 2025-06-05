# PyTorch Learning Repository

Welcome to my PyTorch learning repository! This is a curated collection of PyTorch materials, code examples, and model implementations designed to help beginners start their deep learning journey with PyTorch.

## 🎯 Motivation

When I began learning PyTorch, I found myself scattered across various online resources, tutorials, and documentation. I created this repository to:
- Consolidate the most useful PyTorch learning materials in one place
- Provide clear, practical examples of PyTorch workflows
- Document my learning journey to help others avoid common pitfalls
- Create a reference point for fundamental PyTorch operations and model implementations

This repository is inspired by the resources that helped me learn PyTorch, now organized in a way that I wish existed when I was starting out.

## 🚀 Why Use This Repository?

- **Beginner-Friendly**: Starts with basics and progresses to more advanced concepts
- **Practical Examples**: Focuses on real implementations rather than just theory
- **Modular Structure**: Code is organized for easy understanding and reuse
- **Variety of Models**: Includes different model architectures (TinyVGG, EfficientNet variants)
- **Training Configurations**: Provides examples with different hyperparameters and data sizes

## 📂 Repository Contents

The repository contains:

### Core Modules
- `data_setup.py`: Data loading and preparation utilities
- `model_builder.py`: Model architecture definitions
- `engine.py`: Training and testing functions
- `utils.py` & `helper_functions.py`: Various utility functions

### Training Scripts
- `train.py`: Main training script for image classification

### Pretrained Models
- Various saved model checkpoints with different architectures and training configurations:
  - TinyVGG models
  - EfficientNetB0/B2 models
  - Different training durations (5-10 epochs)
  - Different dataset sizes (10-20% subsets)

## 🏁 Getting Started

1. Clone this repository
2. Install required dependencies (PyTorch, torchvision, etc.)
3. Explore the scripts in order:
   - Start with `data_setup.py` to understand data loading
   - Move to `model_builder.py` for model architectures
   - Examine `engine.py` for training logic
   - Run `train.py` to see everything come together

## 🤝 Contributing

While this is primarily a learning repository, I welcome:
- Corrections to any mistakes
- Suggestions for additional learning materials
- Clearer explanations of concepts

## 📚 Resources That Inspired This Repository

- [PyTorch Official Documentation](https://docs.pytorch.org/docs/stable/index.html)
- [Zero to Mastery PyTorch for Deep Learning](https://www.learnpytorch.io/)
- Various PyTorch tutorial blogs and videos

Happy learning! I hope this repository helps you start your PyTorch journey as effectively as it helped me.
