# 🐱🐶 Cat Dog Image Classifier using CNN

A Deep Learning project that uses a **Convolutional Neural Network (CNN)** to classify images into two categories: **Cat** and **Dog**. The model learns visual features from images and uses them to predict the correct class.

## 📌 Project Overview

The Cat Dog Classifier is a computer vision project developed using Python and TensorFlow/Keras. It demonstrates how deep learning can be applied to image classification by learning patterns such as edges, shapes, textures, and other visual features.

## ✨ Key Features

- 🐱🐶 Binary image classification: Cat or Dog
- 🧠 CNN-based deep learning model
- 🖼️ Image processing using a fixed input size
- 🔍 Feature extraction using convolutional layers
- ⚡ Pooling layers to reduce spatial dimensions
- 📊 Model training and evaluation

## 🛠️ Technologies Used

- **Python** — Programming language
- **TensorFlow & Keras** — Deep learning framework
- **NumPy** — Numerical computations
- **Matplotlib** — Data visualization
- **Google Colab** — Model development and training

## 🧠 Model Architecture

The model uses a Convolutional Neural Network (CNN) with the following components:

1. **Conv2D:** Extracts visual features from input images.
2. **ReLU Activation:** Introduces non-linearity into the network.
3. **AveragePooling2D:** Reduces feature-map dimensions.
4. **Flatten:** Converts feature maps into a one-dimensional vector.
5. **Dense Layers:** Learn patterns for classification.
6. **Output Layer:** Predicts whether the image belongs to the cat or dog class.

*The exact number of layers and output activation depends on the final model implementation.*

## 📂 Dataset

The project uses a dataset of cat and dog images organized into training and testing folders.

Typical structure:

```text
dataset/
├── training_set/
│   ├── cats/
│   └── dogs/
└── test_set/
    ├── cats/
    └── dogs/
```

The training images are used to teach the model, while the test images are used to evaluate its performance on unseen examples.

## ⚙️ Project Workflow

1. Load and organize the image dataset.
2. Preprocess images and resize them to the required dimensions.
3. Build the CNN architecture.
4. Compile the model using an optimizer and loss function.
5. Train the model on the training dataset.
6. Evaluate the model on test images.
7. Use the trained model to classify new images.

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/aparnapandey26/Cat_Dog_Classifier-.git
cd Cat_Dog_Classifier-
```

### 2. Install dependencies

```bash
pip install tensorflow numpy matplotlib
```

### 3. Open the notebook

Open the project notebook in Google Colab or Jupyter Notebook, configure the dataset path, and run the cells in order.

**Note:** The dataset must be available at the path specified in the notebook before training begins.

## 📈 Results

The model is designed to predict whether an input image contains a cat or a dog.

Evaluation metrics such as training accuracy, validation accuracy, and loss can be used to understand the model's performance.

*Add your actual test accuracy and training graphs here after evaluating the final model.*

## 🎯 Learning Outcomes

- Understanding CNN fundamentals
- Learning image preprocessing techniques
- Implementing convolution and pooling layers
- Training a deep learning classification model
- Evaluating image classification performance

## 👩‍💻 Author

**Aparna Pandey**

B.Tech — Computer Science and Engineering (AIML)

GitHub: [@aparnapandey26](https://github.com/aparnapandey26)

---

⭐ If you find this project useful, consider giving the repository a star!
