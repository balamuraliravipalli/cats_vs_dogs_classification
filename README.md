🧵 Fashion-MNIST Classification
📌 Overview

This project uses the Fashion-MNIST dataset to classify clothing images into 10 categories (shirts, shoes, bags, etc.) with deep learning.
We built a baseline Dense model and improved it using a Convolutional Neural Network (CNN).

Final Accuracy: ~89.7% 🎯

📂 Dataset

70,000 grayscale images (28x28)

10 classes: T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot

Train: 60k | Test: 10k

🛠 Steps

Preprocessing → Normalize images, one-hot encode labels

Baseline Model → Dense NN (~85% accuracy)

Improved Model (CNN) → Conv2D, MaxPooling, Dropout, EarlyStopping (~89.7% accuracy)

Evaluation → Confusion matrix + classification report

📊 Results

CNN outperforms Dense model

Some confusion in similar classes (shirt vs T-shirt)

Good overall performance for a simple CNN

🔮 Future Work

Data augmentation

Hyperparameter tuning

Deeper CNNs (VGG, ResNet)

Transfer learning
