# 🛡️ NIS-SYSTEM: Network Intrusion Detection System

A comprehensive machine learning project aimed at identifying unusual or malicious behavior in network traffic. This system enhances cybersecurity by applying both **supervised** and **unsupervised** learning techniques to accurately detect and classify network intrusions.



## 🚀 Project Highlights

- 🔍 Detects both known and unknown threats in near real-time
- ⚙️ Combines supervised and unsupervised ML models for robust intrusion detection
- 📉 Minimizes false positives while maintaining high recall and accuracy
- 🧪 Experimental support for deep learning (scalability testing)



## 📦 Models Implemented

### 🌲 Random Forest Classifier (Supervised)
- Binary classification: `normal` vs. `intrusion`
- Achieved **99.76% accuracy**
- Balanced **precision**, **recall**, and **F1-score**
- Evaluated using **classification report**, **confusion matrix**, and **feature importance**

### 🧊 Isolation Forest (Unsupervised)
- Detects **anomalies** in network behavior
- Useful for identifying novel or unseen attack types
- No need for labeled training data

### 🧬 Neural Network (Optional / Experimental)
- Tested for potential deployment in large-scale, high-traffic environments
- Can model complex traffic patterns, but not used in final evaluation



## 🧰 Tech Stack

- 🐍 Python (NumPy, Pandas, Scikit-learn, TensorFlow/Keras)
- 📁 Network dataset (NSL-KDD or custom CSV)
- 📓 Jupyter Notebook
- 📊 Matplotlib, Seaborn (for visualizations)


## 📊 Data Workflow

1. **Data Preprocessing**  
   - Removed missing values and duplicate records  
   - Converted categorical columns using Label Encoding  
   - Normalized numerical features  

2. **Model Training**  
   - Trained and evaluated Random Forest and Isolation Forest models  

3. **Evaluation**  
   - Metrics: Accuracy, F1-Score, Precision, Recall, ROC-AUC  
   - Addressed warning for undefined precision/recall using `zero_division=0`  
   - **Plotted Confusion Matrix** for visual insight into predictions  
   - **Plotted Feature Importance** for model interpretability  


## 🔎 Key Insights

- ✅ Random Forest achieved strong generalization with balanced metrics
- 🔒 Isolation Forest adds resilience by detecting outliers in real-time
- 📉 Addressed metric warnings by explicitly handling undefined metrics
- 📊 Visuals like confusion matrix and feature importance clarify model behavior
- 💪 The system performs well despite class imbalance



## 💡 Use Cases

- 🔐 Enterprise network intrusion detection
- 🏛️ Cybersecurity for government agencies
- 🌐 Monitoring at ISP-level for unusual activity
- ☁️ Anomaly detection in cloud-based environments



## 📁 Folder Structure

```plaintext
├── data/
│   └── network_traffic.csv
├── notebooks/
│   ├── data_preprocessing.ipynb
│   ├── random_forest_model.ipynb
│   └── isolation_forest_model.ipynb
├── output/
│   ├── confusion_matrix.png
│   └── feature_importance.png
└── README.md



