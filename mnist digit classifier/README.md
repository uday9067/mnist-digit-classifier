# MNIST Handwritten Digit Classifier

This project is a series of experiments on the MNIST handwritten digits dataset using TensorFlow/Keras.  
It covers:
- Dense neural networks with dropout
- Convolutional Neural Networks (CNN)
- Data augmentation for better generalization

## 📂 Project Structure

## 📊 Results
| Version | Model Type                     | Test Loss | Test Accuracy |
|---------|---------------------------------|-----------|---------------|
| V1      | Dense + Dropout                 | 0.1057    | 96.85%        |
| V2      | Deeper Dense + Dropout          | 0.0856    | 97.36%        |
| V3      | CNN                             | 0.0249    | 99.28%        |
| V4      | CNN + Data Augmentation         | 0.0191    | 99.37%        |

## 🚀 How to Run
1. Clone the repo:
   ```bash
   git clone https://github.com/<your-username>/mnist-digit-classifier.git
   cd mnist-digit-classifier
