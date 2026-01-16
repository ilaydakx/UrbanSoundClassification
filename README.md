# Urban Sound Classification using Convolutional Neural Networks (CNN)

This project focuses on classifying urban environmental sounds using a Convolutional Neural Network (CNN).
Audio signals are transformed into Mel spectrograms, enabling the model to automatically learn
time–frequency patterns relevant to urban sound events.

The project demonstrates the application of deep learning techniques to real-world audio
classification problems related to smart cities and environmental monitoring.

---

## 📌 Project Overview
- **Task:** Urban sound classification
- **Number of classes:** 10  
  (dog bark, children playing, car horn, air conditioner, street music, gun shot, siren, engine idling, jackhammer, drilling)
- **Input representation:** 128 × 128 Mel spectrograms
- **Model:** Convolutional Neural Network (CNN)

---

## 🧠 Methodology
1. Audio files were loaded and processed using **Librosa**
2. Audio signals were converted into **Mel spectrograms**
3. Dataset was split into **80% training** and **20% testing**
4. A CNN model was trained using **TensorFlow/Keras**
5. Model performance was evaluated using accuracy metrics and confusion matrices

---

## 🏗️ CNN Architecture
The CNN architecture includes:
- Convolutional layers with **ReLU activation**
- **Batch normalization** for stable training
- **Max pooling** layers for dimensionality reduction
- **Dropout** layers to prevent overfitting
- Fully connected layers with **softmax** output for multi-class classification

---

## 📊 Results
- **Overall accuracy:** approximately **92%**
- High classification performance for sound classes such as *dog bark*, *drilling*, and *gun shot*
- Lower accuracy observed in overlapping sound classes such as *street music* and *car horn*

---

## 🛠️ Technologies Used
- Python
- TensorFlow / Keras
- Librosa
- NumPy
- Matplotlib

---
## 📂 Dataset
This project uses the **UrbanSound8K** dataset, a widely used benchmark dataset for urban sound classification.

- Number of audio clips: 8,732
- Number of classes: 10
- Audio format: WAV
- Duration: ≤ 4 seconds

The dataset is publicly available on Kaggle and is **not included in this repository due to its large size**.

🔗 Dataset link:  
https://www.kaggle.com/datasets/chrisfilo/urbansound8k

---

## 📄 Academic Report
A detailed academic report describing the theoretical background, methodology, and experimental results
is available in the following file:

- `UrbanSound_REPORT.pdf`

---

## 🚀 Future Work
- Experiment with advanced deep learning architectures (e.g., ResNet, RCNN)
- Improve classification performance for overlapping sound events
- Extend the system for real-time urban sound recognition
