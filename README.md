# 📊 Machine Learning Algorithms & Projects

This repository contains **from-scratch implementations, deep learning experiments, and real-world machine learning projects**.  
The focus is on building **strong theoretical foundations**, understanding **model internals**, and applying ML/DL techniques to **practical and research-level problems**.

---

## 📌 Repository Structure

### 🔹 Supervised Learning Algorithms
- Linear Regression  
- Logistic Regression  
- Support Vector Machine (SVM)  
- Decision Tree  
- Naive Bayes Classifier  

### 🔹 Machine Learning & Deep Learning Projects
- SMS Spam Classifier  
- High-Confidence Prediction on CIFAR-100 (Stochastic Depth ResNet-18)  
- Oblique Decision Trees for Credit Card Fraud Detection  

---

## 🧠 Algorithm Implementations

### 1️⃣ Linear Regression
- Implemented regression to model relationships between variables.
- Covered:
  - Cost functions
  - Gradient Descent
  - Model evaluation metrics

📂 Folder: `Linear_Regression/`

---

### 2️⃣ Logistic Regression
- Binary classification using probabilistic modeling.
- Covered:
  - Sigmoid function
  - Decision boundary
  - Loss optimization

📂 Folder: `Logistic_Regression/`

---

### 3️⃣ Support Vector Machine (SVM)
- Margin-based classification model.
- Focused on:
  - Maximum margin hyperplanes
  - Kernel intuition
  - Regularization

📂 Folder: `SVM/`

---

### 4️⃣ Decision Tree
- Tree-based classification model.
- Covered:
  - Information Gain
  - Gini Index
  - Recursive splitting

📂 Folder: `Decision_Tree/`

---

### 5️⃣ Naive Bayes Classifier
- Probabilistic classifier based on Bayes’ Theorem.
- Applied to text-based classification problems.

📂 Folder: `Naive_Bayes/`

---

## 📱 Project: SMS Spam Classifier

### 🔍 Problem Statement
Classify SMS messages as **Spam** or **Ham** using machine learning techniques.

### 🛠 Techniques Used
- Text preprocessing and cleaning
- Feature extraction (Bag of Words / TF-IDF)
- Naive Bayes classification
- Model evaluation using accuracy and precision

📂 Folder: `SMS_Spam_Classifier/`

---

## 🧪 Project: High-Confidence Prediction on CIFAR-100

### 🔍 Problem Statement
Improve **prediction reliability** by producing **high-confidence classifications** on the CIFAR-100 dataset instead of maximizing raw accuracy.

### 🧠 Approach
- Implemented **Stochastic Depth ResNet-18** to improve generalization.
- Introduced **confidence-aware prediction filtering**.
- Calculated an **optimal confidence threshold** using a **skewness-based factor** to balance:
  - Coverage
  - Accuracy
  - Reliability

### 🛠 Techniques Used
- Deep CNNs (ResNet-18)
- Stochastic depth regularization
- Softmax confidence analysis
- Threshold optimization using statistical skewness

### 📈 Outcome
- Achieved significantly higher accuracy on high-confidence predictions
- Demonstrated trade-off between prediction confidence and coverage

📂 Folder: `CIFAR100_High_Confidence_Prediction/`

---

## 🧾 Project: Oblique Decision Trees for Credit Card Fraud Detection

### 🔍 Problem Statement
Detect fraudulent credit card transactions using **non-axis-aligned decision boundaries** for improved classification performance.

### 🧠 Approach
- Implemented **Oblique Decision Trees**, where splits are based on **linear combinations of features**.
- Designed to handle:
  - Highly imbalanced datasets
  - Complex feature interactions

### 🛠 Techniques Used
- Oblique splits using linear classifiers
- Fraud detection on imbalanced data
- Evaluation using precision, recall, and F1-score

### 📈 Outcome
- Improved fraud detection performance compared to standard decision trees
- Better handling of correlated financial features

📂 Folder: `Oblique_Decision_Tree_Fraud_Detection/`

---

## 🧰 Tech Stack
- **Python**
- **NumPy**
- **Pandas**
- **Scikit-learn**
- **PyTorch**
- **Matplotlib / Seaborn**

---

## 🎯 Learning Outcomes
- Strong understanding of **classical ML algorithms**
- Hands-on experience with **deep learning architectures**
- Experience with **confidence-aware prediction systems**
- Practical exposure to **imbalanced classification problems**
- Exposure to **research-oriented ML problem solving**

---

## 🚀 Future Enhancements
- Extend confidence estimation using calibration techniques
- Compare oblique trees with ensemble methods
- Add uncertainty estimation using Bayesian methods
- Improve documentation and visualizations

---

## 👤 Author
**Naman Agrawal**  
Undergraduate Student | Machine Learning & Deep Learning Enthusiast  

📌 Feel free to explore, fork, or contribute!
