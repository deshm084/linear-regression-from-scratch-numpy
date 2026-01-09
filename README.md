# 🧮 Linear Regression from Scratch (NumPy)

## 📌 Overview
This project implements Linear Regression using **Gradient Descent** entirely from scratch using Python and NumPy. No high-level machine learning libraries (like Scikit-Learn) were used for the model logic.

## 🎯 Objective
To deconstruct the "black box" of machine learning by manually implementing:
1.  **Forward Pass:** Calculating linear predictions ($y = wx + b$).
2.  **Cost Function:** Implementing Mean Squared Error (MSE).
3.  **Optimization:** implementing Gradient Descent to minimize loss iteratively.

## ⚙️ How it Works
The model iteratively updates weights using the gradients derived from the error function:
$$w = w - \alpha \cdot \frac{1}{n} \sum_{i=1}^{n} (h_\theta(x^{(i)}) - y^{(i)})x^{(i)}$$

## 🛠️ Tech Stack
* **NumPy:** Matrix operations and vectorization.
* **Matplotlib:** Visualizing the regression line and convergence.
