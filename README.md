# Seizure Detection Using EEG Data with Machine Learning

This repository contains a comprehensive study on detecting epileptic seizures using EEG (Electroencephalogram) data. The project utilizes various Machine Learning models to build a robust classification pipeline. The pipeline includes data cleaning, feature engineering, class balancing, model training, and evaluation. The study aims to aid early seizure detection and contribute to healthcare diagnostics using AI.

---

## 📌 Objectives

- Understand and preprocess EEG data for seizure detection.
- Apply machine learning models to classify seizure and non-seizure events.
- Compare model performance with and without feature engineering and data balancing.
- Provide insights into the effectiveness of each ML approach.

---

## 🧠 Dataset

- **Source**: [Mendeley EEG Epileptic Seizure Recognition Dataset](https://data.mendeley.com/datasets/xyz)
- **Samples**: EEG signals categorized into seizure and non-seizure classes.
- **Features**: Raw EEG recordings with multiple channels.

---

## ⚙️ Project Pipeline

1. **Data Loading and Exploration**
2. **Preprocessing**
   - Handling missing values
   - Signal normalization
   - Artifact removal
3. **Feature Engineering**
   - Time-domain and frequency-domain features
   - Statistical descriptors
4. **Data Balancing**
   - SMOTE / Undersampling / Oversampling
5. **Model Training**
   - Logistic Regression
   - Random Forest
   - Support Vector Machine (SVM)
   - XGBoost
6. **Evaluation**
   - Accuracy, Precision, Recall, F1-Score
   - Confusion Matrix
   - ROC-AUC
7. **Comparison**
   - With vs. without feature engineering
   - With vs. without data balancing

---

## 🛠️ Tools and Libraries

- Python
- NumPy, Pandas
- Scikit-learn
- Matplotlib, Seaborn
- TensorFlow / PyTorch (if extended to DL)
- MNE (for EEG data manipulation)

---

## 👨‍🔬 Authors

- Syed Noor Hussain Shah – BS Data Science, IMSciences
- Supervised by **Dr. Adnan Amin**

---

## 📌 Future Work

- Explore Deep Learning techniques such as CNN, LSTM for time-series EEG data.
- Integrate real-time seizure prediction capability.
- Extend study to multi-class classification (e.g., seizure types).

---

## 📜 License

This project is licensed under the MIT License.

---

## 🤝 Acknowledgements

- Dr. Adnan Amin for guidance and support.
- Mendeley Data for the dataset.

---

## 🔗 Useful Links

- [EEG Seizure Dataset](https://data.mendeley.com/)
- [Scikit-learn Documentation](https://scikit-learn.org/)
- [MNE for EEG](https://mne.tools/)

