# GTSRB Traffic Signs Classification

## Overview
This project implements traffic sign recognition using deep learning on the German Traffic Sign Recognition Benchmark (GTSRB) dataset.

The project includes:
- Dataset exploration and visualization
- Data preprocessing
- Data augmentation
- Custom CNN architecture
- MobileNet transfer learning
- Performance evaluation on the test dataset

---

## Dataset

Dataset: German Traffic Sign Recognition Benchmark (GTSRB)

- 43 traffic sign classes
- Colored traffic sign images
- Image size resized to 32×32
- Multi-class classification problem

Dataset Source:
https://benchmark.ini.rub.de/gtsrb_news.html

---

## Project Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Visualization
4. Data Preprocessing
5. Train-Validation Split
6. Custom CNN Training
7. Data Augmentation
8. MobileNet Transfer Learning
9. Model Evaluation
10. Test Set Prediction

---

## Models Used

### Custom CNN
- Convolution Layers
- Max Pooling
- Dropout
- Dense Layers
- Softmax Output Layer

### MobileNet
- ImageNet Pretrained Weights
- Transfer Learning
- Global Average Pooling
- Classification Head

---

## Technologies Used

- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

---

## Results

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## Repository Structure

├── GTSRB Traffic Signs image classification.ipynb
├── README.md
└── .gitignore

---

## How to Run

1. Clone the repository

git clone https://github.com/ManthanDixit089/GTSRB-Traffic-Signs-Classification.git

2. Install dependencies

pip install -r requirements.txt

3. Open the notebook

jupyter notebook

4. Run all cells

---

## Author

Manthan Dixit

B.Tech CSE (IoT)
