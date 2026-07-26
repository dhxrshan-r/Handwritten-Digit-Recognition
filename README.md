# Handwritten Digit Recognition using Deep Learning (MNIST)

## Overview

This project implements a Handwritten Digit Recognition system using the MNIST dataset and a Deep Learning model built with TensorFlow and Keras. The model is trained to accurately classify handwritten digits from 0 to 9.

The notebook demonstrates the complete machine learning workflow, including:

- Loading and exploring the dataset
- Data preprocessing
- Building and training a neural network model
- Evaluating model performance
- Making predictions on handwritten digits
- Visualizing the results

---

## Dataset Description

The project uses the **MNIST (Modified National Institute of Standards and Technology)** dataset, one of the most widely used benchmark datasets in Machine Learning and Deep Learning.

### Dataset Information

- Total images: **70,000**
- Training images: **60,000**
- Testing images: **10,000**
- Number of classes: **10 (Digits 0–9)**
- Image size: **28 × 28 pixels**
- Pixel value range: **0 to 255**
  - 0 represents black pixels
  - 255 represents white pixels

---

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook / Google Colab

---

## Project Workflow

1. Load the MNIST dataset.
2. Explore the dataset structure and dimensions.
3. Perform data preprocessing and normalization.
4. Split the dataset into training and testing sets.
5. Build a Deep Neural Network using TensorFlow and Keras.
6. Train the model on the training dataset.
7. Evaluate the model's performance.
8. Predict handwritten digits from test samples.
9. Visualize predictions and model outputs.

---

## Model Architecture

The model is built using TensorFlow's Keras Sequential API and consists of fully connected neural network layers.

Typical workflow includes:

- Input Layer
- Hidden Dense Layers
- Activation Functions
- Output Layer with 10 neurons (for digits 0–9)

---

## Installation

Install the required libraries before running the notebook:

```bash
pip install tensorflow==2.18.0
pip install scikit-learn==1.3.2
pip install matplotlib==3.8.3
pip install seaborn==0.13.2
pip install numpy==1.26.4
pip install pandas==2.2.2
```

Or install them together:

```bash
pip install tensorflow==2.18.0 scikit-learn==1.3.2 matplotlib==3.8.3 seaborn==0.13.2 numpy==1.26.4 pandas==2.2.2
```

---

## Running the Project

1. Clone the repository.

```bash
git clone https://github.com/your-username/your-repository-name.git
```

2. Navigate to the project directory.

```bash
cd your-repository-name
```

3. Open the notebook.

```bash
jupyter notebook
```

or upload the notebook to Google Colab.

4. Run all cells sequentially.

> **Note:** If you install the libraries inside the notebook, restart the kernel/runtime before executing the remaining cells.

---

## Results

The trained model is capable of:

- Recognizing handwritten digits from 0 to 9.
- Producing predictions with high accuracy on unseen test images.
- Visualizing handwritten digit samples and prediction outputs.

---

## Repository Structure

```
Handwritten-Digit-Recognition/
│
├── HW_D_RGN_Notebook.ipynb
└── README.md
```

---

## Applications

Handwritten digit recognition is widely used in:

- Postal mail sorting systems
- Bank cheque processing
- Optical Character Recognition (OCR)
- Form digitization
- Automated document processing
- Educational and AI research applications

---

## Learning Outcomes

Through this project, you will learn:

- Deep Learning fundamentals
- Neural Networks using TensorFlow and Keras
- Image classification techniques
- Data preprocessing for image datasets
- Model training and evaluation
- Visualization of machine learning results

---

---

## License

This project is intended for educational and learning purposes.
