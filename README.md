## Research Question
Optimizing Learning Rate Strategies for Stochastic Gradient Descent (SGD)

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
### 2. California Housing Dataset

**Why Choose This?**  
The California Housing dataset consists of 20,640 samples of housing data, including 8 features such as median income, housing age, and average rooms. It is more complex than MNIST and is used for regression tasks.

**Types of Experiments**  
This dataset is particularly useful for testing how well the learning rate strategies can generalize in regression tasks, providing insight into model performance and error reduction.

**Link:** [California Housing Dataset on Kaggle](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
