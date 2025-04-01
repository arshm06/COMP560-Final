Research Question: Optimizing Learning Rate Strategies for Stochastic Gradient Descent (SGD)

## Methods
The methods explored for tuning the learning rate include:

- **SGD Method:** Constant learning rate
- **Cyclical Learning Rates**
- **Conditional Based Learning Rate using Sigmoid**

## Test Datasets

### 1. MNIST Handwritten Digit Recognition Dataset

**Why Choose This?**  
MNIST is a classic dataset used in computer vision, comprising 70,000 grayscale images of handwritten digits (0-9). 
**Types of Experiments**  
This dataset can be used to test basic SGD, Cyclical Learning Rates, and other conditional methods in a controlled setting. The uniformity of data type means that learning dynamics can be clearly observed.

**Link:** [MNIST Dataset on Kaggle](https://www.kaggle.com/c/digit-recognizer/data)

---

### 2. CIFAR-10 Dataset

**Why Choose This?**  
The CIFAR-10 dataset consists of 60,000 32x32 color images in 10 classes, with 6,000 images per class. The dataset is more complex than MNIST, involving color images with more variability in content.

**Types of Experiments**  
This dataset is particularly useful for seeing how well the aforementioned stratigies can generalize across different image types and prevent overfitting.

**Link:** [CIFAR-10 Dataset on Kaggle](https://www.kaggle.com/c/cifar-10/data)
