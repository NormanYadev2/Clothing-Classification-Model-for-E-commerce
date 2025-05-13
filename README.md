🧠 CNN for Image Classification using FashionMNIST
🎯 Project Aim
This project develops an automated product tagging system for e-commerce platforms using Convolutional Neural Networks (CNNs).
The model classifies product images into predefined categories, improving:

📦 Inventory management

🔍 Product searchability

🤖 Recommendation systems

📂 Dataset Used
FashionMNIST
🔗 Kaggle Link

This dataset contains 28x28 grayscale images of fashion products from 10 categories:

👕 T-shirt/top

👖 Trouser

🧥 Pullover

👗 Dress

🧥 Coat

👡 Sandal

👔 Shirt

👟 Sneaker

👜 Bag

👢 Ankle boot

Each image is labeled from 0 to 9, corresponding to the category.

🏗️ Model Architecture

The model is a basic CNN with:

Conv2D layer with 16 filters
ReLU activation
MaxPooling2D layer
Flatten layer
Fully connected Linear layer


📊 Evaluation Metrics

Accuracy: Overall correctness
Precision (per class): True positives / (True positives + False positives)
Recall (per class): True positives / (True positives + False negatives)

