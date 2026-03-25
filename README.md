# CNN Dog Breed Classifier (Transfer Learning)

## Overview
Developed a computer vision application that detects whether an image contains a human or a dog, classifies dog breeds across 133 categories, and maps human faces to visually similar dog breeds.

Improved model performance from ~10% accuracy (baseline CNN) to ~86% test accuracy by implementing transfer learning using DenseNet-161.

---

## Key Features
- Detects humans using Haar Cascade classifiers
- Classifies dog breeds across 133 categories
- Maps human faces to visually similar dog breeds
- Built with PyTorch

---

## Model Architecture
- Baseline: Custom CNN (~10% accuracy)
- Final Model: DenseNet-161 (pretrained)
- Transfer learning with frozen feature extractor
- Custom classifier head:
  - Linear → ReLU → Dropout → Linear → LogSoftmax

---

## Results
- Baseline CNN Accuracy: ~10%
- Transfer Learning Model Accuracy: ~86%
- Significant improvement through feature reuse and fine-tuning

---

## Tech Stack
- Python
- PyTorch
- torchvision
- NumPy
- OpenCV (Haar Cascades)

---

## Project Structure
