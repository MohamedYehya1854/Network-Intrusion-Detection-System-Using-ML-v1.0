# Network Intrusion Detection System Using ML (v1)

## 📌 Project Overview
This project presents a **Machine Learning–based Network Intrusion Detection System (IDS)** designed to identify malicious network activities and distinguish them from normal traffic. It leverages the **NSL-KDD dataset**, a refined version of the KDD’99 dataset, to build and evaluate intelligent detection models.

This repository represents **Version 1 (Prototype)** of the system and serves as a foundation for future enhancements and optimizations.

---

## 🎯 Objectives
- Analyze network traffic data and detect potential intrusions
- Apply Machine Learning techniques for anomaly and attack detection
- Evaluate the effectiveness of different models and preprocessing strategies
- Build a scalable and extensible IDS prototype for future development

---

## 🧠 Methodology
The project follows a structured Machine Learning pipeline:

1. **Data Loading & Exploration**
   - Load NSL-KDD dataset
   - Inspect features, labels, and class distribution

2. **Data Preprocessing**
   - Handling categorical features using **One-Hot Encoding**
   - Feature scaling and normalization
   - Separation of features and target labels

3. **Feature Engineering**
   - Selection of relevant network traffic attributes
   - Preparation of datasets suitable for ML models

4. **Clustering (Unsupervised Learning)**
   - Apply clustering techniques to analyze traffic behavior
   - Identify hidden patterns and anomalies in network data

5. **Classification (Supervised Learning)**
   - Train Machine Learning models to classify traffic as **Normal** or **Attack**
   - Evaluate performance using standard metrics

6. **Model Evaluation**
   - Confusion Matrix
   - Accuracy, Precision, Recall, and F1-Score

---

## 🛠️ Technologies & Tools
- **Programming Language:** Python
- **Libraries & Frameworks:**
  - NumPy
  - Pandas
  - Scikit-learn
  - Matplotlib / Seaborn
- **Environment:** Jupyter Notebook
- **Dataset:** NSL-KDD

---

## 📊 Dataset Information
- **Name:** NSL-KDD
- **Type:** Network intrusion detection dataset
- **Classes:** Normal traffic & multiple attack categories
- **Purpose:** Benchmarking IDS models and research

> The NSL-KDD dataset addresses redundancy and imbalance issues found in the original KDD’99 dataset, making it more suitable for Machine Learning experiments.

---

## 📁 Project Structure
```
├── IntrusionDetectionSystem.ipynb
├── README.md
└── dataset/
    └── NSL-KDD
```

---

## 🚀 How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/MohamedYehya1854/Network-Intrusion-Detection-System-Using-ML-v1.0.git
   ```
2. Navigate to the project directory
3. Open the Jupyter Notebook:
   ```bash
   jupyter notebook IntrusionDetectionSystem.ipynb
   ```
4. Run the cells sequentially

---

## 📈 Results
- Successfully distinguished between normal and malicious traffic
- Demonstrated the effectiveness of Machine Learning techniques in network security
- Provided a solid baseline for further optimization and experimentation

---

## 🧩 Limitations (v1)
- Prototype implementation (not production-ready)
- Limited hyperparameter tuning
- Dataset-specific (NSL-KDD)

---

## 🔮 Future Work
- Improve model accuracy with advanced algorithms
- Apply deep learning techniques
- Real-time intrusion detection support
- Cross-dataset evaluation
- Deployment-ready architecture

---

## 👨‍💻 Author
**Mohamed Altantawy Yehya**  
Information Technology Graduate – Cyber Security Focus

---

## 🤝 Acknowledgments & Contributors
The following individuals contributed to or supported this project:

- **Dr. Sara Emara**  
  Information Technology Department, Faculty of Computers & Information, Mansoura University

- **Eng. Mostafa Abdrabo**  
  Project Partner and Core Team Member


---

## 📜 License
This project is intended for **educational and research purposes only**.

---

⭐ If you find this project useful, feel free to star the repository and follow for future updates.

