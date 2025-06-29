# E-Waste Generation Classification
## 🧠 Project Description
- Trained on a dataset of 10 E-Waste classes (e.g., Battery, Mobile, PCB, etc.)
- Used **EfficientNetV2B0** as the base model with transfer learning.
- Added data augmentation and dropout to improve generalization.
- Evaluated using accuracy, loss curves, and a confusion matrix.
- Final model deployed with **Gradio** for real-time image predictions.

## 📁 Dataset Structure
The dataset is organized into:
- `train/` – for training the model
- `val/` – for validation during training
- `test/` – for evaluating final accuracy
Each folder contains 10 subfolders for each class label.

## 📊 Model Performance
-Validation Accuracy: ~95%+

-Visual performance confirmed via confusion matrix and sample predictions

## 🧩 Tools & Technologies
-Python

-TensorFlow / Keras

-EfficientNetV2B0 (Transfer Learning)

-Gradio

-Matplotlib / Seaborn

-Scikit-learn


