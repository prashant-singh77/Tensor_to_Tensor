# Tensor2Tensor Deep Learning & Transformer Experiments

A hands-on introduction to **Tensor2Tensor (T2T)** covering dataset
preparation, MNIST image classification, pre-trained Transformer-based
English-to-German translation, attention visualization, and custom model
training using TensorFlow.

## 📌 Project Overview

This project explores the core capabilities of Tensor2Tensor, including:

-   Working with Tensor2Tensor datasets and problems
-   Downloading and inspecting the MNIST dataset
-   Using a pre-trained Transformer model for English-to-German
    translation
-   Encoding and decoding text using Tensor2Tensor encoders
-   Visualizing Transformer attention weights
-   Creating a custom Tensor2Tensor model
-   Training a custom model on MNIST
-   Evaluating model performance using accuracy metrics

## 🛠️ Technologies Used

-   Python
-   TensorFlow
-   Tensor2Tensor
-   NumPy
-   Matplotlib
-   Google Colab

## 📂 Project Structure

``` text
Tensor2Tensor-Project/
│
├── tensor2tensor_intro.py
└── README.md
```

## 🚀 Features

### 1. MNIST Dataset

The project downloads the MNIST dataset through Tensor2Tensor and
prepares it for training and evaluation.

### 2. Transformer Translation

A pre-trained Transformer model is loaded to translate text from English
to German.

Example input:

``` text
The animal didn't cross the street because it was too tired
```

The project encodes the input, runs inference using the pre-trained
checkpoint, and decodes the model output.

### 3. Attention Visualization

The project extracts encoder, decoder, and encoder-decoder attention
weights from the Transformer model and visualizes them to help
understand how the model attends to different tokens.

### 4. Custom MNIST Model

A custom Tensor2Tensor model is created using convolutional layers and
trained on the MNIST dataset.

The training pipeline includes:

-   Dataset preparation
-   Batch processing
-   Adam optimizer
-   Training loop
-   Loss monitoring
-   Evaluation
-   Accuracy metrics

## ⚙️ Installation

The original project installs the required packages with:

``` bash
pip install -U tensor2tensor
pip install tensorflow matplotlib
```

> **Note:** The uploaded project is based on an older
> TensorFlow/Tensor2Tensor environment, so modern TensorFlow versions
> may not be fully compatible with the original code.

## ▶️ How to Run

### Google Colab

The project was originally created as a Google Colab notebook. You can
upload `tensor2tensor_intro.py` to a Colab environment or convert the
code into notebook cells.

### Local Environment

Create a Python environment and install the required dependencies:

``` bash
pip install -U tensor2tensor
pip install tensorflow matplotlib numpy
```

Then run:

``` bash
python tensor2tensor_intro.py
```

## 📚 What I Learned

Through this project, I explored:

-   Deep learning datasets and preprocessing
-   TensorFlow model training
-   Transformer architecture concepts
-   Machine translation
-   Text encoding and decoding
-   Attention mechanisms
-   Custom neural network development
-   Model evaluation

## 🎯 Project Purpose

The main purpose of this project is to gain practical experience with
**deep learning, Tensor2Tensor, Transformer models, computer vision, and
natural language processing** through hands-on experimentation.

## 👨‍💻 Author

**Alpha**

------------------------------------------------------------------------

⭐ If you find this project useful, consider giving the repository a
star!
