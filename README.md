#  Iris Flower Classification using Artificial Neural Networks (ANN)

##  Project Overview
This project implements an **Artificial Neural Network (ANN)** to classify iris flowers into three species—**Setosa, Versicolor, and Virginica**—based on their sepal and petal measurements. The model leverages deep learning techniques to learn patterns from the data and accurately predict the species of unseen samples.

---

##  Objective
The objective of this project is to build a robust multi-class classification model using an Artificial Neural Network and evaluate its ability to classify iris flowers with high accuracy.

---

##  Dataset Information
The **Iris dataset** is one of the most widely used datasets in machine learning and consists of **150 observations** with four numerical features:

- Sepal Length (cm)
- Sepal Width (cm)
- Petal Length (cm)
- Petal Width (cm)

### Target Classes
- **Setosa**
- **Versicolor**
- **Virginica**

---

##  Technologies Used
- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook

---

##  Workflow
1. Data Loading and Exploration
2. Data Preprocessing
3. Feature Scaling
4. Label Encoding
5. Train-Test Split
6. Building the Artificial Neural Network
7. Model Training
8. Performance Evaluation
9. Prediction on Unseen Data

---

##  Model Architecture
- Input Layer: 4 Neurons
- Hidden Layer(s): Dense Layers with ReLU Activation
- Output Layer: 3 Neurons with Softmax Activation
- Loss Function: Categorical Crossentropy
- Optimizer: Adam
- Evaluation Metric: Accuracy

---

##  Results
The ANN model successfully classified iris flower species with high accuracy, demonstrating the effectiveness of deep learning for multi-class classification problems.

### Performance Metrics
- Accuracy Score
- Confusion Matrix
- Classification Report

---

##  Features
✔ Multi-class classification using ANN  
✔ Data preprocessing and normalization  
✔ Deep learning implementation with TensorFlow/Keras  
✔ Prediction on unseen data  
✔ Performance evaluation using accuracy and classification metrics  

---

##  Project Structure

```
├── iris ANN deep learning.ipynb
├── README.md
├── requirements.txt
└── dataset/
```

---

##  How to Run

### Clone the Repository

```bash
git clone https://github.com/yourusername/iris-flower-classification-ann.git
```

### Navigate to the Project Directory

```bash
cd iris-flower-classification-ann
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
iris ANN deep learning.ipynb
```

---

##  Conclusion
This project demonstrates how Artificial Neural Networks can effectively solve multi-class classification problems. By learning patterns from flower measurements, the model accurately predicts the species of iris flowers and showcases the potential of deep learning techniques in predictive analytics.

---

##  Future Enhancements
- Hyperparameter tuning for improved accuracy.
- Experiment with deeper neural network architectures.
- Deploy the model using Streamlit or Flask.
- Build an interactive web application for real-time predictions.
---



###  If you found this project useful, please give it a star!
