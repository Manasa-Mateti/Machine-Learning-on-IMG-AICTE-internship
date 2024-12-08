# Implementation-of-ML-model-for-image-classification
Implementation-of-ML-model-for-image-classification  is a fundamental task in computer vision with applications ranging from medical imaging to autonomous vehicles. This project showcases a simple yet effective implementation of an image classification model.

##Model Architecture

The default model is a Convolutional Neural Network (CNN) with the following architecture:

Input layer for image dimensions (e.g., 32x32x3 for CIFAR-10).
Convolutional layers with ReLU activation and max pooling.
Fully connected layers with dropout for regularization.
Softmax output layer for classification.

## Key Features

- **Dual Model Support**:
  - **MobileNetV2 (ImageNet)**: Recognizes 1,000 different classes from the ImageNet dataset, including everyday objects, animals, and vehicles.
  - **Custom CIFAR-10 Model**: Specializes in classifying images into one of ten specific categories such as airplanes, automobiles, and birds.

- **Intuitive Interface**:
  - **Navigation Bar**: Seamlessly switch between MobileNetV2 and CIFAR-10 models using a sleek sidebar menu.
  - **Real-Time Classification**: Upload an image to receive immediate predictions with confidence scores.

- **Educational and Practical Use**:
  - Ideal for learning about deep learning models and their performance.
  - Useful for practical applications where image classification is needed.

## Getting Started

### Prerequisites

- Python 3.7 or later
- A web browser

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/JayRathod341997/DeepLensX.git
   cd Implementation-of-ML-model-for-image-classification
2. **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate   # On Windows use `venv\Scripts\activate`
3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
4. **Start the Streamlit app**:
    ```bash
    streamlit run app.py
5. **Open the app**: 
    The app will open in your default web browser. If not, navigate to http://localhost:8501

### Contributing
  Feel free to fork the repository, open issues, or submit pull requests to contribute to the project.

### Acknowledgements
  - Streamlit
  - TensorFlow
