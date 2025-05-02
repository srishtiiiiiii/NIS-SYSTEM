
# 🛡️ NIS-SYSTEM: Network Intrusion Detection System

A comprehensive machine learning project aimed at identifying unusual or malicious behavior in network traffic. This system enhances cybersecurity by applying both **supervised** and **unsupervised** learning techniques to accurately detect and classify network intrusions.


## 🚀 Project Highlights

- 🔍 Detects both known and unknown threats in real-time
- ⚙️ Combines multiple machine learning models for greater robustness
- 📉 Minimizes false positives while maintaining high recall
- 🧪 Experimental integration of deep learning for scalability


## 📦 Models Implemented

### 🌲 Random Forest Classifier (Supervised)
- Binary classification: `normal` vs. `intrusion`
- Achieved **99.76% accuracy**
- Balanced performance with high **precision** and **recall**

### 🧊 Isolation Forest (Unsupervised)
- Detects **anomalies** without requiring labeled data
- Effective for identifying new or evolving threats
- Suitable for continuous network monitoring

### 🧬 Neural Network (Optional / Experimental)
- Evaluated for potential in large-scale deployments
- Can handle complex traffic patterns in high-volume environments


## 🧰 Tech Stack

- 🐍 Python (NumPy, Pandas, Scikit-learn, TensorFlow)
- 📁 Network dataset (e.g., NSL-KDD or custom CSV)
- 📈 Jupyter Notebooks / Google Colab
- 🛠️ Matplotlib / Seaborn for visualizations


## 📊 Data Workflow

1. **Data Cleaning** – Removed missing values, duplicates, and irrelevant columns  
2. **Feature Engineering** – Encoded categorical features, normalized data  
3. **Model Training** – Applied and evaluated RF, Isolation Forest, and Neural Network  
4. **Evaluation** – Used metrics like Accuracy, F1-Score, Precision, ROC-AUC  
5. **Interpretation** – Plotted confusion matrix and feature importance


## 🔎 Key Insights

- 📌 Ensemble learning (RF) captures patterns effectively for labeled data
- 🧠 Isolation Forest adds a **zero-trust** layer for anomaly detection
- 🔁 Combining models improves **generalization** and **real-world reliability**
- 📈 High performance even with imbalanced datasets

## 💡 Use Cases

- 🔐 Enterprise network security
- 🏛️ Government cybersecurity systems
- 🌐 ISP-level traffic monitoring
- ☁️ Cloud infrastructure anomaly detection


