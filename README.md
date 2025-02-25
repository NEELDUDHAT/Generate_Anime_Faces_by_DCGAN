# DCGAN Anime Face Generator

This repository contains an implementation of a **Deep Convolutional Generative Adversarial Network (DCGAN)** to generate high-quality anime faces.

## 🚀 Features
- Trains a **DCGAN** to generate anime-style faces.
- Implements a **Generator** and **Discriminator** using deep learning.
- Uses **TensorFlow/Keras** for model training.
- Supports **custom dataset loading and training modifications**.
- Generates **high-resolution, diverse anime faces**.

## 📌 Prerequisites
Make sure you have the following installed:
- Python (>=3.7)
- TensorFlow (>=2.x)
- NumPy
- Matplotlib
- tqdm (for progress tracking)
- Kaggle API (for dataset download, if needed)

## 📂 Dataset
The model is trained on a dataset of anime faces. You can download it from Kaggle:

🔗 **Dataset Link**: [Anime Faces Dataset](https://www.kaggle.com/datasets/soumikrakshit/anime-faces)

To download the dataset using the Kaggle API:
```bash
pip install kaggle
kaggle datasets download -d soumikrakshit/anime-faces
unzip anime-faces.zip -d dataset/
