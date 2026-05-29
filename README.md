AI-Powered Cat and Dog Image Classification

 🧠 Project Overview
This project is a Deep Learning-based Image Classification system that classifies images as either a cat or a dog using a Convolutional Neural Network (CNN).

The model is trained using Keras and TensorFlow on a dataset of labeled cat and dog images.

📊 Dataset Overview
- Source: Kaggle / Custom Dataset
- Total Images: ~10,000
  - Training Images: 8,000
  - Testing Images: 2,000
- Classes:
  - Cats 🐱
  - Dogs 🐶

 Preprocessing:
- Image resizing to 64x64
- Normalization (0–1 scaling)
- Data augmentation (flip, zoom, shear)

 🏗️ Model Architecture
- Convolution Layer
- MaxPooling Layer
- Flatten Layer
- Dense Layer (128 neurons)
- Output Layer (Sigmoid)

⚙️ Technologies Used
- Python
- TensorFlow / Keras
- NumPy
- Google Colab

 📈 Training Details
- Optimizer: Adam
- Loss Function: Binary Crossentropy
- Batch Size: 32
- Epochs: 1 (can be increased)
- Accuracy: ~65–68%

 🚀 How It Works
1. Image is resized to 64x64
2. Converted into array
3. Passed through CNN model
4. Output:
   - 0 → Cat
   - 1 → Dog



## 📌 Future Improvements
- Increase epochs
- Use Transfer Learning (VGG16 / ResNet)
- Improve accuracy
- Deploy as web app (Flask / Streamlit)



## ⭐ Outcome
This project demonstrates image classification using Convolutional Neural Networks (CNN).