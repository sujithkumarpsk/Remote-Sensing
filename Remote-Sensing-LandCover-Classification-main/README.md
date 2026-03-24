🌍 Multispectral Image Classification

This project focuses on classifying land cover types using multispectral satellite imagery. Unlike standard RGB images, multispectral data contains multiple spectral bands, allowing better feature extraction and improved classification accuracy.

📌 Overview

The model is built using a Convolutional Neural Network (CNN) trained on multispectral images. It can identify different land cover classes such as vegetation, urban areas, water bodies, and more.

🚀 Features
Supports multispectral (multi-band) image inputs
Custom CNN model built from scratch
Handles non-RGB satellite data
Good generalization across land cover classes
🗂️ Dataset
Dataset used: EuroSAT (Sentinel-2)
Contains 13 spectral bands per image
Includes multiple land cover categories
🧠 Model
Convolutional Neural Network (CNN)
Layers include:
Convolutional layers
Activation (ReLU)
Pooling layers
Fully connected layers
⚙️ Installation
git clone https://github.com/your-username/multispectral-image-classification.git
cd multispectral-image-classification
pip install -r requirements.txt
▶️ Usage
python train.py

For testing:

python test.py
📊 Results
Achieves good accuracy on validation data
Performs well across different land types
🛠️ Technologies Used
Python
TensorFlow / PyTorch
NumPy, Matplotlib
📌 Future Improvements
Improve accuracy with advanced architectures (ResNet, EfficientNet)
Add real-time prediction support
Deploy as a web application
👨‍💻 Author
Your Name
