# Handwritten Digit Recognition using Deep Learning

A Deep Learning project that classifies handwritten digits 0-9 using the MNIST dataset with a Dense Neural Network built in TensorFlow/Keras.

## **Project Overview**
This project demonstrates building, training, and evaluating a neural network from scratch to recognize handwritten digits. 
The model achieves 97.6% accuracy on the MNIST test set without using any pre-trained models.

## **Dataset**
**MNIST - Modified National Institute of Standards and Technology**
- 60,000 training images
- 10,000 test images  
- 28x28 grayscale images of handwritten digits 0-9
- Loaded directly using `tf.keras.datasets.mnist`

## **Model Architecture**
Dense Neural Network with 3 layers:

| Layer | Neurons | Activation | Parameters |
| --- | --- | --- | --- |
| Flatten | - | - | 0 |
| Dense | 128 | ReLU | 100,480 |
| Dense | 32 | ReLU | 4,128 |
| Dense | 10 | Softmax | 330 |

**Total Parameters: 104,938**

## **Results**
- **Training Accuracy**: 99.30%
- **Validation Accuracy**: 97.69%
- **Epochs**: 10
- **Optimizer**: Adam
- **Loss Function**: Sparse Categorical Crossentropy

### Loss & Accuracy Graphs
![Accuracy Graph](accuracy_plot.png)
![Loss Graph](loss_plot.png)

## **Technologies Used**
- Python 3.x
- TensorFlow 2.x / Keras
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## **How to Run**
1.  Clone this repository
    ```bash
    git clone https://github.com/yourusername/mnist-dl-project.git
## **Author**
Muhammad Awais khan

⭐If you found this project helpful please give a star⭐ 
