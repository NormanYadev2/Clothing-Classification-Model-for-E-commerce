# 🧠 CNN for Image Classification using FashionMNIST

## 🎯 Project Aim

This project develops an **automated product tagging system** for e-commerce platforms using **Convolutional Neural Networks (CNNs)**.  
The model classifies product images into predefined categories, improving:

- 📦 Inventory management  
- 🔍 Product searchability  
- 🤖 Recommendation systems

---

## 📂 Dataset Used

**FashionMNIST**  
📎 [Kaggle Dataset](https://www.kaggle.com/datasets/zalando-research/fashionmnist/data)

FashionMNIST consists of **28×28 grayscale images** of fashion items from **10 categories**:

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

The CNN architecture includes:

- 🧠 `Conv2D` layer with 16 filters (kernel size = 3)  
- ⚡ `ReLU` activation  
- 🌀 `MaxPooling2D` (kernel size = 2)  
- 🧱 `Flatten` layer  
- 🎯 Fully connected `Linear` layer for 10-class classification  

---

## 🧪 Evaluation Metrics

Performance of the model is measured using:

- ✅ **Accuracy**  
  *Overall correctness of predictions.*

- 🎯 **Precision (per class)**  
  *True Positives / (True Positives + False Positives)*

- 📈 **Recall (per class)**  
  *True Positives / (True Positives + False Negatives)*

---

## 🛠️ Tools & Libraries

- `PyTorch`
- `Torchvision`
- `Torchmetrics`
- `NumPy`
