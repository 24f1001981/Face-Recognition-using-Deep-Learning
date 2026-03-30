# Face-Recognition-using-Deep-Learning


This project implements a multi-class face recognition system using Convolutional Neural Networks (CNNs) on the LFW (Labeled Faces in the Wild) dataset.

---

## 📌 Project Overview

- 📊 Dataset: LFW (Labeled Faces in the Wild)  
- 👥 Classes: 60+ individuals  
- 🖼️ Images: 3000+  
- 🎯 Task: Multi-class face classification  

The model is trained to identify individuals from facial images and evaluate performance using validation metrics and visualizations.

---

## ⚙️ Features

-  Data filtering (minimum images per person)
-  Data augmentation (flip, rotation, zoom)
-  CNN-based image classification model
-  Model saving & loading (no retraining required)
-  Training history saving & replay
-  Accuracy & loss visualization
-  Confusion matrix for performance analysis
-  Prediction testing with correct/incorrect outputs

---

## 🧠 Model Architecture

- Conv2D → MaxPooling  
- Conv2D → MaxPooling  
- Conv2D → MaxPooling  
- Flatten  
- Dense (256 units) + Dropout  
- Output layer (Softmax)

---

## 📈 Results

-  Validation Accuracy: ~65%  
-  Handles 60+ classes with limited data per class  

---

## 📊 Visualizations

The project includes:

- 📈 Training vs Validation Accuracy  
- 📉 Training vs Validation Loss  
- 📊 Confusion Matrix  
- 👤 Prediction Results (Correct / Incorrect)

---


## 💡 Key Learnings

- Handling multi-class classification with limited data  
- Importance of data augmentation  
- Optimizing training using caching and prefetching  
- Avoiding retraining using model & history persistence  
- Evaluating models beyond accuracy (confusion matrix)

---

## 🔗 Future Improvements

-  Use transfer learning (MobileNetV2 / ResNet)  
-  Improve accuracy with better architectures  
-  Real-time face recognition using webcam  
-  Deploy as a web application  

---

## 👩‍💻 Author

Shreya S N

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
