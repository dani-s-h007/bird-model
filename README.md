# 🐦 Bird Classifier with FastAI

A simple binary image classification model to detect whether an image contains a **bird** or **not** using FastAI and ResNet18.

## 🚀 Features

- Clean dataset with auto-image verification and resizing.
- Trained using FastAI's `vision_learner` with `resnet18`.
- Supports testing images from direct **online URLs**.
- Minimal and reproducible codebase (Colab ready).
- Model exported for easy reuse and inference (`.pkl` file).

## 🧠 Model

- Architecture: `ResNet18`
- Framework: [FastAI](https://docs.fast.ai/)
- Training: Fine-tuned for 3 epochs with an 80-20 split.