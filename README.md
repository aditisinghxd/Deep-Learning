# MNIST Handwritten Digits Recognition - Image Classification

## Dataset Information
### This dataset allows you to study, analyze and recognize elements in the images. That’s exactly how your camera detects your face, using image recognition! It’s a digit recognition problem. This data set has 49,000 images of 28 X 28 size, totalling 49 MB.
### Download link: https://datahack.analyticsvidhya.com/contest/practice-problem-identify-the-digits/
## Libraries
The following libraries are used for this project:

- **pandas**: Data manipulation and analysis.
- **matplotlib**: Plotting and visualization.
- **keras**: High-level neural networks API.
- **tensorflow**: Backend engine for deep learning.
- **scikit-learn**: Machine learning library.

## Model Used
A basic **Convolutional Neural Network (CNN)** is used to recognize the digits with high accuracy. CNNs are particularly effective for image classification tasks due to their ability to capture spatial hierarchies in images.

### Neural Network Architecture:
- **Input layer**: 28x28 grayscale images
- **Convolutional layers**: Feature extraction
- **Pooling layers**: Downsampling
- **Fully connected layers**: Classification

### Accuracy Achieved:
- **98.38%**
