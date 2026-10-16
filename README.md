# Handwritten Digit Recognition Using Neural Networks

## Overview
This project uses a neural network to recognize handwritten digits from 0 to 9. It uses image pixel values to train a deep learning model and predict the correct digit.

## Objectives
- Load and preprocess the handwritten digit dataset.
- Build and train a neural network using TensorFlow and Keras.
- Predict handwritten digits from image pixel values.
- Evaluate the model using accuracy, loss, and a confusion matrix.
- Visualize training performance and incorrect predictions.

## Dataset
- **Dataset file:** `mnist_data.csv`
- **Dataset size:** 8,035 rows before preprocessing
- **Image dimensions:** 28 × 28 pixels
- **Input features:** 784 pixel values
- **Target:** Digit labels from 0 to 9

## Technologies Used
- Python
- Pandas and NumPy
- Matplotlib
- Scikit-learn
- TensorFlow and Keras

## Neural Network Architecture
- Input layer: 784 features
- Hidden layer 1: 128 neurons with ReLU
- Dropout layer: 20%
- Hidden layer 2: 64 neurons with ReLU
- Output layer: 10 neurons with Softmax

## Project Workflow
1. Dataset loading
2. Data preprocessing and missing-value handling
3. Pixel normalization
4. Train/test split
5. Neural network creation
6. Model training
7. Digit predictions
8. Model evaluation
9. Accuracy and loss graphs
10. Confusion matrix and conclusion

## Results
- **Test Accuracy:** 94.34%
- **Test Loss:** 0.193
- **Incorrect Predictions:** 91 out of 1,607 test examples

## Future Improvements
- Implement a Convolutional Neural Network (CNN).
- Use data augmentation to improve generalization.
- Tune model hyperparameters.
- Test the model on new handwritten digit images.

## Conclusion
The project demonstrates how neural networks can classify handwritten digits using image pixel data. The model achieved 94.34% test accuracy, showing promising performance while leaving room for improvement.

