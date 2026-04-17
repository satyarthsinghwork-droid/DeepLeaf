
## Overview
This project builds a **Plant Disease Classification model** using **TensorFlow and Keras**.  
It uses **EfficientNetV2B0 (transfer learning)** to classify plant leaf images into disease categories.

---

## Features
- Transfer learning with EfficientNetV2B0
- Image classification using deep learning
- Dataset loading with `image_dataset_from_directory`
- Model training & validation
- Accuracy and loss visualization
- Model saving for reuse

---

##  Model Architecture
- EfficientNetV2B0 (pretrained on ImageNet)
- Global Average Pooling
- Batch Normalization
- Dense output layer

---

##  Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Matplotlib
- Pandas
- Seaborn

---

## Dataset
- Plant Disease Dataset (Augmented)
- Organized into training and validation directories

---

##  How to Run

1. Install dependencies:
pip install tensorflow numpy matplotlib pandas seaborn

2. Update dataset paths in notebook

3. Run:
jupyter notebook main.ipynb

---

## Output
- Training accuracy & validation accuracy graphs
- Loss curves
- Saved trained model

---

##  Model Saving
model.keras

Load later:
```python
import tensorflow as tf
model = tf.keras.models.load_model("model.keras")
```

---

##  Use Cases
- Smart agriculture
- Disease detection in crops
- Automated plant monitoring

---

##  Future Improvements
- Add deployment (web/app)
- Improve dataset diversity
- Use TensorFlow Lite for mobile

