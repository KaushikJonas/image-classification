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


| Layer Type     | Description                  |
|----------------|------------------------------|
| Conv2D         | Extracts image features      |
| MaxPooling     | Downsamples feature maps     |
| Dropout        | Prevents overfitting         |
| Dense          | Fully connected layers       |
| Softmax Output | Predicts probabilities       |

---
![Screenshot 2025-07-03 141820](https://github.com/user-attachments/assets/e0fd13d4-c8e8-425c-8e01-ed2a0e4c5631)
![Screenshot 2025-07-03 141843](https://github.com/user-attachments/assets/a41a7b4b-9db9-4bd8-968c-d313c651c91f)

## ✅ Output

`The notebook will train your CNN model on the CIFAR-10 dataset.`

`You will see the training progress for each epoch inside the notebook.`

`It will display training accuracy and loss after each epoch.`

`The final test accuracy will be shown after evaluation.`

`All results, including accuracy and loss, will be visible within the notebook cells.`


## 📊 Results (CIFAR-10 CNN)

| 🔢 Parameter         | 🔍 Value                                 |
| -------------------- | ---------------------------------------- |
| 📦 Dataset           | CIFAR-10                                 |
| 🖼️ Image Size       | 32 × 32 (RGB)                            |
| 🔟 Number of Classes | 10                                       |
| 🏋️ Epochs           | 10                                       |
| 🗂️ Batch Size       | 25                                       |
| ⚙️ Optimizer         | Adam                                     |
| 🎯 Loss Function     | Categorical Crossentropy                 |
| 🏆 Test Accuracy     | \~74%                                    |
| ⏳ Training Status    | Completed Successfully                   |
| 🚀 Model Type        | Basic Convolutional Neural Network (CNN) |
