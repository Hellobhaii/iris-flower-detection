# 🌼 Iris Flower Detection (Machine Learning Project)

This project predicts the **species of an Iris flower** (Setosa, Versicolor, Virginica) using a machine learning model trained on the classic Iris dataset.  
It includes training, evaluation, and prediction scripts.

---

## 🔍 Overview

This project demonstrates:
- Loading and preprocessing the Iris dataset  
- Training machine learning models  
- Evaluating accuracy  
- Saving/loading the trained model  
- Predicting species from input features  

---

## 📂 Project Structure

```
iris_project/
│── data/                    # dataset (optional)
│── models/                  # saved trained model (pkl/joblib)
│── notebooks/               # Jupyter notebooks
│── src/
│   ├── train.py             # training script
│   ├── predict.py           # prediction script
│   └── utils.py             # helper functions
│── requirements.txt
│── README.md
```

---

## 🛠 Installation

Clone this repository:

```bash
git clone https://github.com/Hellobhaii/iris-flower-detection.git
cd iris-flower-detection
```

Install required Python packages:

```bash
pip install -r requirements.txt
```

---

## 🚀 Train the Model

To train the model:

```bash
python src/train.py
```

This will:
- Train a model  
- Save it inside the `models/` folder  

---

## 🔮 Predict Using the Model

You can predict using command line inputs:

```bash
python src/predict.py 5.1 3.5 1.4 0.2
```

Example Output:

```
Predicted Species: Iris-setosa
```

---

## 📊 Model Accuracy

Typical accuracy ranges from **95% to 98%**, depending on the ML algorithm used (KNN, SVM, Logistic Regression, etc.).

---

## 🙌 Author

**Chirag Agarwal (Hellobhaii)**  
Machine Learning / Python Enthusiast

---

## 📝 License

This project is free to use for learning and academic purposes.
