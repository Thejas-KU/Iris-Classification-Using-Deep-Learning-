# Deep Learning Iris Classification 🌸

## 📌 Overview
This project uses a **Deep Learning model** to classify **Iris flowers** into three species — *Setosa*, *Versicolor*, and *Virginica* — based on their petal and sepal measurements. Implemented in Python using **TensorFlow/Keras**.

## 📊 Dataset
- **Source**: [Iris Dataset](https://archive.ics.uci.edu/ml/datasets/iris)
- **Features**:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- **Target Classes**:
  - 0 → Setosa
  - 1 → Versicolor
  - 2 → Virginica

## 🛠 Requirements
Install dependencies with:
bash
pip install -r requirements.txt
Main libraries used:

Python 3.x

TensorFlow / Keras

NumPy

Pandas

Matplotlib / Seaborn

Scikit-learn

🚀 How to Run
Clone this repository

bash
Copy code
git clone https://github.com/yourusername/Deep-Learning-Iris-Classification.git
Open the notebook:

bash
Copy code
jupyter notebook Deep_Learning_Iris_Classification.ipynb
Run all cells to train and test the model.

🧠 Model Architecture
Input layer: 4 neurons (features)

Hidden layers: Dense layers with ReLU activation

Output layer: 3 neurons with Softmax activation

Optimizer: Adam

Loss: Categorical Crossentropy

📈 Results
Model achieves high accuracy (>95%) on test data

Confusion matrix shows correct classification for most samples

Visualization of training and validation accuracy/loss provided

📌 Author
Thejas K U
Feel free to fork, use, and contribute! 🚀
