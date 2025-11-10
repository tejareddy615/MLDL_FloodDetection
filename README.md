# MLDL_FloodDetection
Flood area segmentation using U-Net (Intermediate Update 1 for MLDL Project).

# Flood Area Segmentation – MLDL Intermediate Update 1

**Author:** Teja Reddy Mandadi , Visesh Bentula, Umapathi Konduri
**Course:** Machine Learning & Deep Learning (MLDL)  
**Date:** November 2025  

This repository contains the initial implementation for the Flood Area Segmentation project using a **U-Net CNN** trained on the **Faizal Karim Flood Area Dataset**.

## Contents
- `flood_segmentation_unet.ipynb` – preprocessing, model training, evaluation
- `loss_curve.png` – Training and Validation loss plot

##  Model Summary
- **Model:** U-Net (PyTorch)
- **Optimizer:** Adam (lr = 1e-4)
- **Loss Function:** Binary Cross-Entropy
- **Dataset:** [Flood Area Segmentation (Faizal Karim)](https://www.kaggle.com/datasets/faizalkarim/flood-area-segmentation)
- **Results:**  
  - Train Loss ≈ 0.31  
  - Validation Loss ≈ 0.39  
  - Mean IoU ≈ 0.62  

## How to Run
1. Clone this repository or open in JupyterLab / Colab.  
2. Install dependencies:  
   ```bash
   pip install torch torchvision matplotlib pillow tqdm

##  Next Steps
- Add data augmentation (flips, rotations)
- Experiment with ResNet-based U-Net encoder
- Add precision, recall, and Dice metrics

