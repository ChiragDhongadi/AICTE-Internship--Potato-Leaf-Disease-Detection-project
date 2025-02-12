# AICTE-Internship--Potato-Leaf-Disease-Detection-project

Potato Leaf Disease Detection

📌 Overview

This project aims to detect and classify potato leaf diseases using deep learning. It leverages a Convolutional Neural Network (CNN) trained on a dataset of potato leaf images to identify diseases such as Late Blight, Early Blight, and Healthy leaves. The system provides an easy-to-use interface for farmers and agricultural experts to upload leaf images and receive instant disease predictions.

🚀 Features

Deep Learning-Based Detection: Uses a CNN model for accurate classification.

User-Friendly Interface: Built with Streamlit for seamless image uploads and predictions.

High Accuracy: Trained on a well-labeled dataset for optimal performance.

Real-Time Predictions: Provides instant feedback on the uploaded image.

🛠️ Tech Stack

Python

TensorFlow/Keras (Deep Learning Framework)

OpenCV (Image Processing)

Streamlit (Web App Interface)

Matplotlib & Seaborn (Visualization)

📂 Dataset

The dataset consists of images of potato leaves categorized into three classes:

Potato___Late_blight

Potato___Early_blight

Potato___Healthy

📊 Model Performance

Training and validation accuracy graphs show a steady increase, achieving a high accuracy of 90%+ on validation data, ensuring reliable predictions.

🔥 Installation

Follow these steps to set up and run the model locally:

# Clone the repository
git clone https://github.com/your-username/potato-leaf-disease-detection.git
cd potato-leaf-disease-detection

# Install dependencies
pip install -r requirements.txt

# Run the Streamlit app
streamlit run app.py

🎯 Usage

Open the Streamlit app.

Upload an image of a potato leaf.

Click on the Predict button.

The model will classify the disease and display the result.

🔍 Future Improvements

Increase dataset size for better generalization.

Improve model robustness against environmental factors (e.g., lighting conditions).

Implement mobile-friendly deployment for on-the-go predictions.

🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.
