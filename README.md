# Anamolous-Event-Detection# Anomalous Event Detection using Deep Learning

This project focuses on detecting anomalous events in videos using deep learning models. The **UCF-Crime** dataset is used for training and evaluation, leveraging **Python 3.11** and deep learning frameworks.

## 🚀 Project Overview

Anomalous event detection is crucial in security and surveillance. This project utilizes deep learning techniques to identify unusual activities in video sequences. A **Convolutional LSTM Autoencoder** is trained to learn normal video patterns and detect deviations as anomalies.

## 📂 Dataset

- **UCF-Crime Dataset**: A large-scale dataset containing normal and anomalous video samples.
- The dataset consists of multiple categories of anomalies, such as fights, accidents, and thefts.
- Frames are extracted from video sequences and preprocessed before training.

## 🛠️ Technologies Used

- **Python 3.11**
- **TensorFlow / Keras** (for deep learning)
- **OpenCV** (for video processing)
- **NumPy, Pandas** (for data handling)
- **Matplotlib, Seaborn** (for visualization)

## 📌 Model Architecture

- **Convolutional LSTM Autoencoder**  
  - Captures spatial and temporal features in video sequences.  
  - Trained on normal events to reconstruct frames.  
  - Anomalies are detected based on reconstruction errors.

