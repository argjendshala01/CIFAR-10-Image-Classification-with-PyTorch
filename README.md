# CIFAR-10 Image Classification with PyTorch


This project demonstrates image classification on the CIFAR-10 dataset using two different approaches:
1. Custom Convolutional Neural Network (CNN)
2. Transfer Learning with ResNet-18

We applied data augmentation and normalization using torchvision to improve generalization. The dataset was split properly into training, validation, and test sets to ensure fair evaluation. A custom CNN was implemented from scratch, and transfer learning was also explored using a pre‑trained ResNet‑18 model.

Training and validation loops were built with automatic saving of the best model during training. After training, we reported per‑class accuracy to understand performance across categories. Misclassifications were visualized to highlight where the model struggled, and a confusion matrix along with a classification report provided a detailed breakdown of results.
