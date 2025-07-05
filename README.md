
# Autoencoder Denoising – PlantVillage Dataset 🌿

**Author:** Ghazaleh Alizadehbirjandi  
**Due Date:** July 5, 2025

---

## 📌 Objective

This project explores the application of **autoencoders** for **image denoising** using the **PlantVillage dataset**. The goal is to compare the effectiveness of three architectures:
- MLP-Based Autoencoder
- Convolutional Autoencoder
- Hybrid CNN + MLP Autoencoder

---

## 🗃️ Dataset

The dataset was provided via SharePoint and contains:
- `Pure_Dataset` (clean images)
- `Noisy_Dataset` (same images with Gaussian noise)
- Split into `Train_Data` and `Test_Data`

---

## 🧠 Models Implemented

| Model              | Type             | Summary |
|-------------------|------------------|---------|
| MLP Autoencoder   | Fully Connected  | Learns rough shapes, poor detail |
| CNN Autoencoder   | Convolutional    | Better structure, still blurry |
| Hybrid Autoencoder| CNN + Dense bottleneck | Slight improvement, preserves both shape and some structure |

Each model was trained using MSE loss and evaluated visually and numerically.

---

## 📊 Results

Visualizations compare:
- **Noisy Input**
- **Denoised Output**
- **Clean Target**
![result1](https://github.com/user-attachments/assets/cc79cec8-31fd-4b23-9471-d0983618d869)
![result2](https://github.com/user-attachments/assets/3d56eb98-5b9b-429a-8c48-e52839aee359)
![result3](https://github.com/user-attachments/assets/d44f93b9-d5df-44cf-99a0-f4d01088ea23)


### 🔍 Summary Table

| Model    | Strengths                      | Weaknesses                |
|----------|--------------------------------|---------------------------|
| MLP      | Fast, learns shape             | Very blurry outputs       |
| CNN      | Preserves structure            | Still lacks fine detail   |
| Hybrid   | Blends both, best of the three | Still needs improvement   |





