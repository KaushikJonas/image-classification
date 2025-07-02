# image-classification-using-cnn--in--cifar
![Screenshot 2025-07-02 184724](https://github.com/user-attachments/assets/53f43244-2e34-40d0-84db-d6c923c96ac3)
# 🧠 CIFAR-10 Image Classification using CNN

This project implements a Convolutional Neural Network (CNN) using TensorFlow/Keras to classify images from the **CIFAR-10** dataset. The model is trained for **10 epochs** and achieves around **74% test accuracy**.

---

## 📊 Dataset: CIFAR-10

The CIFAR-10 dataset consists of 60,000 color images (32x32 pixels) across 10 classes:

- ✈️ Airplane
- 🚗 Automobile
- 🐦 Bird
- 🐱 Cat
- 🦌 Deer
- 🐶 Dog
- 🐸 Frog
- 🐴 Horse
- 🚢 Ship
- 🚚 Truck

Split:
- 50,000 training images
- 10,000 test images

---

## 🧠 Model Architecture

CNN model architecture:

Input → Conv2D(32) → MaxPooling → Dropout
→ Conv2D(64) → MaxPooling → Dropout
→ Flatten → Dense(128) → Dropout → Dense(10, Softmax)

yaml
Copy
Edit

| Layer Type     | Description                  |
|----------------|------------------------------|
| Conv2D         | Extracts image features      |
| MaxPooling     | Downsamples feature maps     |
| Dropout        | Prevents overfitting         |
| Dense          | Fully connected layers       |
| Softmax Output | Predicts probabilities       |

---

## 🧪 Results

| Metric        | Value         |
|---------------|---------------|
| Test Accuracy | **~74%**      |
| Epochs        | **10**        |
| Optimizer     | Adam          |
| Loss          | Categorical Crossentropy |
| Batch Size    | 64            |

---



