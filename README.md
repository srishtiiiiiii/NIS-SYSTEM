# 🛡️ NIS-SYSTEM: Network Intrusion Detection System

A focused machine learning project that detects unusual or malicious activity in network traffic. This system enhances cybersecurity by using both **supervised** and **unsupervised** learning techniques to identify intrusions effectively.



## 🚀 Project Highlights

- 🔍 Detects both known and unknown network threats
- ⚙️ Uses supervised (Random Forest) and unsupervised (Isolation Forest) models
- 📉 Reduces false positives while maintaining high recall and accuracy
- 🧪 Experimental integration of deep learning considered but not finalized



## 📦 Models Implemented

### 🌲 Random Forest Classifier (Supervised)
- Performs binary classification: `normal` vs. `intrusion`
- Achieved **99.76% accuracy**
- Evaluated using:
  - Classification report (Precision, Recall, F1-score, Accuracy)
  - Confusion matrix
    
 
### 🧊 Isolation Forest (Unsupervised)
- Detects **anomalies** without needing labeled data
- Useful for spotting new or evolving attacks
- Suitable for continuous background monitoring



## 🧰 Tech Stack

- 🐍 Python (NumPy, Pandas, Scikit-learn)
- 📁 Network traffic dataset 
- 📓 Jupyter Notebook( VS Code)
- 📊 Matplotlib for plotting (no Seaborn used)



## 📊 Data Workflow

1. **Data Cleaning**  
   - Removed missing values and duplicates  
   - Dropped irrelevant features  

2. **Feature Engineering**  
   - Label encoded categorical features  
   - Normalized numerical values  

3. **Model Training & Testing**  
   - Trained and evaluated Random Forest Classifier  
   - Applied Isolation Forest for anomaly detection  

4. **Evaluation**  
   - Generated classification report and confusion matrix  

Key features like `src_bytes`, `dst_bytes`, and `same_srv_rate` were the most impactful in identifying intrusions.



## 🔎 Key Insights

- ✅ Random Forest performed robustly across metrics
- 🚨 Class imbalance handled gracefully with appropriate evaluation parameters
- 📉 Visualization of feature importances helped understand model decisions
- 🔍 Isolation Forest provided a complementary anomaly detection layer



## 💡 Use Cases

- 🏢 Enterprise-level network security monitoring  
- 🛡️ Cybersecurity in government infrastructure  
- 🌐 ISP and telecom traffic surveillance  
- ☁️ Anomaly detection in cloud environments  



