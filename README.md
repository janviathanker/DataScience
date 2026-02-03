# DataScience 
neural network classifier
# Neural Network from Scratch – Character Classification (A, B, C)

## 📌 Project Overview
This project implements a **feedforward neural network from scratch using NumPy** to classify binary image patterns representing the characters **A, B, and C**.  
No external machine learning libraries such as TensorFlow or PyTorch are used.

Each character is represented as a **5×6 binary pixel grid (30 pixels)**.  
The neural network learns to classify these characters using **backpropagation and gradient descent**.

---

## 🎯 Objectives
- Understand the internal working of a neural network
- Implement forward propagation and backpropagation manually
- Learn weight initialization, activation functions, and loss calculation
- Visualize training performance using loss and accuracy plots

---

## 📂 Dataset
No external dataset is used.  
The input data consists of **manually defined binary pixel patterns** for:
- Letter A
- Letter B
- Letter C

Each image is flattened into a 30-dimensional vector.

---

## 🧠 Neural Network Architecture

| Layer        | Description |
|--------------|------------|
| Input Layer  | 30 neurons (5×6 pixels) |
| Hidden Layer | 16 neurons (Sigmoid activation) |
| Output Layer | 3 neurons (A, B, C – One-hot encoded) |

---

## ⚙️ Technologies Used
- Python
- NumPy
- Matplotlib
- Jupyter Notebook

---

## 🔁 Training Details
- Activation Function: Sigmoid
- Loss Function: Mean Squared Error (MSE)
- Optimizer: Gradient Descent
- Learning Rate: 0.1
- Epochs: 5000

---

## 📊 Results
- The model successfully learns to classify all three characters
- Training loss decreases steadily
- Accuracy converges to 100% on training data
- Input images and training graphs are visualized using Matplotlib

---

## 📈 Visualizations
- Training Loss vs Epochs
- Training Accuracy vs Epochs
- Binary image display of input characters

---

## 📌 How to Run
1. Clone the repository or download the notebook
2. Open the `.ipynb` file in Jupyter Notebook
3. Run all cells sequentially

---

## 🧪 Testing
The trained model is tested using sample character inputs (A, B, or C) and predicts the correct class.

---

## 📝 Conclusion
This project provides hands-on experience with the core building blocks of neural networks and strengthens understanding of how learning occurs internally without relying on high-level ML frameworks.

---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# COVID-19 Data Analysis

This project analyzes global COVID-19 confirmed cases and deaths, and correlates them with worldwide happiness indicators.

## Tools Used
- Python
- Pandas
- Matplotlib
- Seaborn

## Key Findings
- High GDP countries showed higher confirmed cases.
- Happiness had weak relation with COVID outcomes.
- Social support showed minimal protective effect.

## Files
- covid_analysis.ipynb – main notebook
- covid19_Confirmed_dataset.csv
- covid19_deaths_dataset.csv
- worldwide_happiness_report.csv
