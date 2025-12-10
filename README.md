# CS523 – Dog Breed Recognition

This repository contains code for our CS523 project on open-set dog breed recognition.

## Files

- `baseline_mobilenetv2.ipynb`  
  Transfer-learning baseline using MobileNetV2 on 120 dog breeds.

- `convnext_9498_open_set.ipynb`  
  ConvNeXt-Base model with strong MLP head, layer-wise learning rate decay (LLRD),
  EMA, and a confidence-based open-set rule. This is the model that achieves **94.98%**
  validation accuracy on the 121-class open-set benchmark (120 known breeds + 1 Unknown).

## Usage

1. Install dependencies (PyTorch, torchvision, timm, etc.).
2. Download the Stanford Dogs dataset and construct the Unknown class from Oxford-IIIT Pet as described in our report.
3. Run the notebooks in order to reproduce the baseline and final results.
