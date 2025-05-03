# GAN-Data-Poisoning-MNIST-Sentiment

# GAN and Data Poisoning Projects
## 👨‍🎓 Student Info

- **Name:** Manikanta Rajulapati
- ****StudenID:** 700762001
- **Course:** CS5720 Neural Networks & Deep Learning
- **University:** University of Central Missouri
- **Semester:** Spring 2025

---

This repository contains two machine learning projects implemented in **PyTorch** and **scikit-learn**:

1. 🧠 **Generative Adversarial Network (GAN)** on the MNIST dataset  
2. ⚠️ **Data Poisoning Simulation** on a simple Sentiment Classifier

---

## 📁 Project Structure

```
gan-data-poisoning-mnist-sentiment/
├── gan_mnist/
│   ├── train_gan.py                 # GAN implementation using PyTorch
│   └── gen_epoch_0_50_100.png      # Sample outputs from Generator
├── sentiment_poisoning/
│   ├── sentiment_model.py          # Sentiment classifier & poisoning simulation
│   └── data_poisoning_comparison.png # Accuracy/Confusion matrix before vs. after attack
├── README.md                       # Project explanation and instructions
└── requirements.txt                # Dependencies
```

---

## 🧠 Project 1: GAN on MNIST

This project implements a **basic GAN** trained on the **MNIST** dataset to generate realistic handwritten digits.

### 🛠 Technologies:
- PyTorch
- torchvision
- matplotlib

### 🎯 Objectives:
- Define Generator and Discriminator networks
- Train using adversarial loss
- Output sample images at epoch 0, 50, and 100
- Track generator and discriminator loss over time

### 📷 Sample Outputs:
Images are saved at:
```
gan_mnist/gen_epoch_0.png
gan_mnist/gen_epoch_50.png
gan_mnist/gen_epoch_100.png
```

---

## ⚠️ Project 2: Data Poisoning on Sentiment Classifier

This simulation shows how a **data poisoning attack** can mislead a basic text sentiment classifier.

### 🛠 Technologies:
- scikit-learn
- pandas
- matplotlib
- seaborn

### 🎯 Objectives:
- Train logistic regression on text sentiment data
- Poison reviews that mention "UC Berkeley" by flipping their labels
- Compare model performance before and after poisoning

### 📊 Results:
- Accuracy and confusion matrix are saved in `data_poisoning_comparison.png`

---

## 🚀 How to Run

### 1. Install dependencies:
```bash
pip install -r requirements.txt
```

### 2. Run GAN training:
```bash
cd gan_mnist
python train_gan.py
```

### 3. Run Sentiment poisoning:
```bash
cd sentiment_poisoning
python sentiment_model.py
```

---



## 📜 License

This project is for educational use only.
