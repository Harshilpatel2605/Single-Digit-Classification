# Single-Digit-Classification

# MNIST Digit Classification using Naïve Bayes

This project implements a **Naïve Bayes classifier** for digit classification using the **MNIST dataset**. The model is trained on binarized MNIST images and can predict handwritten digits from an input image.

## 🚀 Features
- Loads the **MNIST dataset** from OpenML.
- Binarizes the dataset for Naïve Bayes classification.
- Implements **Naïve Bayes with Laplace smoothing**.
- Accepts a **custom image** as input and predicts the digit.

## 📦 Dependencies
Ensure you have the following Python libraries installed:
```bash
pip install numpy scikit-learn pillow
```

## 📂 File Structure
```
│-- mnist_naive_bayes.py  # Main script
│-- README.md             # Project documentation
```

## 🛠 Usage
### 1️⃣ Run the Script
```bash
python mnist_naive_bayes.py
```

### 2️⃣ Input an Image
When prompted, enter the **file path** of the image you want to classify.

### 3️⃣ Output Example
```
Enter the image name: digit.png
From the image, model predicted the number to be 3 with probability 0.87
```

## 📊 How It Works
1. Loads the **MNIST dataset** and binarizes it.
2. Splits the data into training and testing sets.
3. Trains a **Naïve Bayes model** using conditional probabilities.
4. Accepts an image, converts it to **28×28 grayscale**, binarizes it, and flattens it.
5. Predicts the digit using **log probabilities** to prevent underflow.

## 📝 Notes
- Ensure the image is **28×28 pixels** for best accuracy.
- Images should be **grayscale** (or will be converted automatically).
- The model assumes the dataset follows a **Bernoulli distribution** (binary features).

