# Satellite-Image-Classification-Using-Deep-Learning
A deep learning project that classifies satellite imagery into land cover categories using a CNN trained on the EuroSAT dataset.

# 🌍 About
This project builds a Convolutional Neural Network (CNN) to classify satellite images into various land use and land cover categories using the **EuroSAT dataset**, a collection of RGB satellite imagery derived from Sentinel-2.

---

## 📊 Dataset

- **Source**: [EuroSAT - Sentinel-2 Satellite Images](https://github.com/phelber/eurosat)
- **Classes (10)**: 
  - AnnualCrop, Forest, HerbaceousVegetation, Highway, Industrial, Pasture, PermanentCrop, Residential, River, SeaLake
- **Size**: 27,000+ RGB images (64×64)

---

## 🧠 Project Objectives

- Build and train a CNN using PyTorch to classify satellite imagery.
- Improve model performance with data augmentation, validation, and dropout.
- Visualize model performance using accuracy/loss curves.
- Evaluate with validation accuracy and confusion matrix.
- Save and reload the trained model.

---

## 🛠️ Tech Stack

| Component        | Technology             |
|------------------|-------------------------|
| Language         | Python                  |
| Deep Learning    | PyTorch                 |
| Data Processing  | Torchvision, PIL        |
| Visualization    | Matplotlib              |
| Dataset          | EuroSAT (via torchvision) |

---



