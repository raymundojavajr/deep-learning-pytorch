# Deep Learning with PyTorch

This repository contains Jupyter notebooks for my learning and understanding of deep learning concepts using PyTorch.

## **Notebooks**

- **Iris Classification:** [`Iris_Classification_Neural_Network.ipynb`](Iris_Classification_Neural_Network.ipynb)
  - Implements a neural network to classify the **Iris dataset**.

- **MNIST CNN:** [`MNIST_CNN_Training_PyTorch.ipynb`](MNIST_CNN_Training_PyTorch.ipynb)
  - Trains a **Convolutional Neural Network (CNN)** for **MNIST digit classification**.

## **Setup Instructions**

### **1. Clone the Repository**
```bash
git clone https://github.com/raymundojavajr/deep-learning-pytorch.git
cd deep-learning-pytorch
```

### **2. Create a Virtual Environment**
```bash
uv venv .venv
source .venv/bin/activate  # macOS/Linux
# or
.venv\Scripts\activate  # Windows
```

### **3. Install Dependencies**
```bash
uv pip install -r requirements.txt
```

### **4. Run Jupyter Notebook**
```bash
jupyter notebook
```

---

## **Pre-commit & Linting**
This project uses `pre-commit` and `ruff` for linting and formatting.

### **Run Pre-commit Hooks Manually**
```bash
pre-commit run --all-files
```

### **Run Ruff for Linting**
```bash
ruff check .
```

---

## **Contributing**
Feel free to fork this repository and submit **pull requests** for improvements.

---

## **License**
This project is licensed under the **MIT License**.

---
