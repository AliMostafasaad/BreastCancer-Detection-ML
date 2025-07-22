# 🧠 Breast Cancer Detection using Machine Learning

A simple machine learning project to classify breast cancer using Logistic Regression, Decision Tree, and Random Forest.  
It also includes a web interface built with Flask.

---

## 📊 Dataset
The dataset is based on [Breast Cancer Wisconsin Diagnostic Data Set](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29).

---

## 🚀 How to Run the Project

1. **Clone the repository:**

```bash
git clone https://github.com/AliMostafasaad/BreastCancer-Detection-ML.git
cd BreastCancer-Detection-ML
```

2. **Create and activate a virtual environment (optional):**

```bash
python -m venv venv
venv\Scripts\activate  # On Windows
```

3. **Install the required libraries:**

```bash
pip install -r requirements.txt
```

4. **Run the app:**

```bash
python app.py
```

---

### 🚨 If you get a FileNotFoundError or the model is missing:
Run the training script to generate the model file:

```bash
python train_model.py
```
## 🛠️ Built With

- Python 3.10
- Scikit-learn
- Flask
- Pandas
- Numpy
## 📂 Folder Structure

```
├── app.py
├── train_model.py
├── models/
│   └── model.pkl
├── templates/
│   └── index.html
├── static/
├── requirements.txt
└── README.md
```

---

## 👤 Author

- [Ali Mostafa](https://github.com/AliMostafasaad)
