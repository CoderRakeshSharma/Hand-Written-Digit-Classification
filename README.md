# Handwritten Digit Classification

This project demonstrates the classification of handwritten digits from the MNIST dataset using a Convolutional Neural Network (CNN) built with TensorFlow/Keras.

## Table of Contents
- [Dataset](#dataset)
- [Data Exploration](#data-exploration)
- [Model Architecture](#model-architecture)
- [Evaluation](#evaluation)
- [Challenges and Solutions](#challenges-and-solutions)
- [Results](#results)
- [How to Run](#how-to-run)

## Dataset
The MNIST dataset contains 60,000 training images and 10,000 test images of handwritten digits, ranging from 0 to 9.

## Data Exploration
- Visualized sample images and their corresponding labels.
- Observed the distribution of digits to ensure balanced representation.

## Model Architecture
A CNN was implemented with the following layers:
1. **Convolutional Layer**: Feature extraction.
2. **Max Pooling Layer**: Dimensionality reduction.
3. **Flatten Layer**: Preparing data for the Dense layers.
4. **Dense Layers**: Fully connected layers for classification.

## Evaluation
The model achieved high accuracy on the test dataset. Performance metrics included accuracy, precision, recall, and confusion matrix analysis.

## Challenges and Solutions
### Image Preprocessing
- **Challenge**: Original images had dimensions and color channels incompatible with the model input.
- **Solution**: Resized images to `28x28` pixels and converted them to grayscale.

## Results
- Achieved **X%** accuracy on the test set.
- Model performance was robust across various digit samples.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/handwritten-digit-classification.git
   ```
2. Install required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook:
   ```bash
   jupyter notebook Handwritten_Digit_Classification_Code.ipynb
   ```

## Acknowledgements
- MNIST Dataset: [Yann LeCun's website](http://yann.lecun.com/exdb/mnist/)
- TensorFlow Documentation: [TensorFlow.org](https://www.tensorflow.org/)
