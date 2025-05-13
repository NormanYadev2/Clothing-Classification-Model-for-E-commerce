# 🧠 CNN for Image Classification using FashionMNIST

## 🎯 Project Aim

This project develops an automated **product tagging system** for e-commerce platforms using **Convolutional Neural Networks (CNN)**.  
The model classifies product images into predefined categories, improving:

- 📦 Inventory Management  
- 🔍 Product Searchability  
- 💡 Recommendation Systems

---

## 🧾 Dataset Used

**Fashion MNIST** – [View Dataset on Kaggle](https://www.kaggle.com/datasets/zalando-research/fashionmnist/data)

The dataset consists of **28x28 grayscale images** of fashion products across **10 categories**:

| Label | Category     |
|-------|--------------|
| 0     | T-shirt/top  |
| 1     | Trouser      |
| 2     | Pullover     |
| 3     | Dress        |
| 4     | Coat         |
| 5     | Sandal       |
| 6     | Shirt        |
| 7     | Sneaker      |
| 8     | Bag          |
| 9     | Ankle boot   |

---

## 🏗️ Model Architecture

A simple yet powerful **Convolutional Neural Network (CNN)**:

- 📥 **Conv2D Layer** (16 filters, kernel size 3×3, padding=1)
- ⚡ **ReLU Activation**
- 📉 **MaxPooling2D** (kernel size 2×2)
- 🧾 **Flatten Layer**
- 🔗 **Fully Connected Linear Layer**

---

## 📊 Evaluation Metrics

The model performance was evaluated using the following metrics:

- ✅ **Accuracy**: Overall correctness of predictions
- 🎯 **Precision (per class)**: `TP / (TP + FP)`
- 🔁 **Recall (per class)**: `TP / (TP + FN)`

---

## 📈 Model Performance

| Metric               | Value        |
|----------------------|--------------|
| **Epoch**            | 0            |
| **Loss**             | 0.0409       |
| **Overall Accuracy** | **88.6%**    |

### 🎯 Precision per Class

| Class        | Precision |
|--------------|-----------|
| T-shirt/top  | 0.8290    |
| Trouser      | 0.9683    |
| Pullover     | 0.8446    |
| Dress        | 0.8720    |
| Coat         | 0.8163    |
| Sandal       | 0.9904    |
| Shirt        | 0.7134    |
| Sneaker      | 0.9024    |
| Bag          | 0.9642    |
| Ankle boot   | 0.9547    |

### 📊 Recall per Class

| Class        | Recall   |
|--------------|----------|
| T-shirt/top  | 0.8580   |
| Trouser      | 0.9780   |
| Pullover     | 0.8100   |
| Dress        | 0.8990   |
| Coat         | 0.8400   |
| Sandal       | 0.9240   |
| Shirt        | 0.6620   |
| Sneaker      | 0.9710   |
| Bag          | 0.9700   |
| Ankle boot   | 0.9480   |

---

## 🛠️ Requirements

```bash
torch
torchvision
torchmetrics
matplotlib
