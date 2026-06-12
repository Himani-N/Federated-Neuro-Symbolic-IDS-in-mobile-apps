# Federated-Neuro-Symbolic-IDS-in-mobile-apps

# FNS-IDS: A Federated Neuro-Symbolic Intrusion Detection System for Zero-Day Threat Detection in Mobile Applications

## 📌 Overview

FNS-IDS (Federated Neuro-Symbolic Intrusion Detection System) is an advanced cybersecurity framework designed to detect both known and unknown (zero-day) threats in mobile applications.

The system integrates:

- Federated Learning (FL) for privacy-preserving distributed training
- Deep Learning (DNN/RNN/LSTM) for behavioral pattern recognition
- Symbolic Reasoning for explainable decision-making
- Multi-Modal Feature Analysis using network traffic, system calls, application permissions, and contextual device signals

Unlike traditional Intrusion Detection Systems (IDS), FNS-IDS enables collaborative model training without sharing sensitive user data, making it suitable for modern mobile environments.

---

## 🎯 Problem Statement

Traditional IDS solutions suffer from several limitations:

- Dependence on centralized data collection
- Difficulty detecting zero-day attacks
- Privacy concerns due to raw data sharing
- Limited interpretability of machine learning models
- High false positive rates

FNS-IDS addresses these challenges through a hybrid federated neuro-symbolic architecture.

---

## 🚀 Objectives

- Detect zero-day threats in mobile applications
- Preserve user privacy using Federated Learning
- Improve intrusion detection accuracy
- Reduce false positives and false negatives
- Provide explainable security decisions
- Support scalable distributed deployment

---

## 🏗️ System Architecture

```text
Mobile Devices
      │
      ▼
Data Collection
      │
      ▼
Data Preprocessing
      │
      ▼
Feature Extraction
      │
      ▼
Neural Encoding
(DNN / RNN / LSTM)
      │
      ▼
Symbolic Reasoning
(IF-THEN Rules)
      │
      ▼
Neuro-Symbolic Fusion
      │
      ▼
Attack Prediction
      │
      ▼
Local Model Updates
      │
      ▼
Federated Server
(FedAvg Aggregation)
      │
      ▼
Global Model Distribution
      │
      ▼
Updated Local Models
```

---

## ⚙️ Key Features

### Privacy-Preserving Learning
- Local training on user devices
- No raw data sharing
- Only model updates are transmitted

### Neuro-Symbolic Intelligence
- Deep learning-based pattern recognition
- Rule-based symbolic reasoning
- Improved explainability

### Zero-Day Attack Detection
- Detects previously unseen threats
- Learns evolving attack behaviors

### Multi-Modal Analysis
Combines:
- Network Traffic
- System Calls
- Application Permissions
- Device Context Signals

### Federated Learning
- Distributed model training
- FedAvg aggregation
- Scalable architecture

---

## 📂 Dataset Information

### UNSW-NB15

A benchmark intrusion detection dataset containing:

- Normal Traffic
- DoS Attacks
- Exploits
- Reconnaissance
- Worms
- Fuzzers

Features:
- 45 Features
- 82,332 Records

### CIC-MalDroid

Android malware dataset containing:

- Benign Applications
- Malicious Applications
- System Calls
- Execution Patterns
- Resource Utilization

### Real-Time Data

Apache Kafka is used for:

- Streaming Logs
- Network Packets
- Real-Time Threat Monitoring

---

## 🧠 Technologies Used

| Category | Technology |
|-----------|------------|
| Programming Language | Python |
| Deep Learning | TensorFlow |
| Neural Network Framework | Keras |
| Deep Learning Research | PyTorch |
| Machine Learning | Scikit-Learn |
| Federated Learning | TensorFlow Federated |
| Data Processing | Pandas |
| Numerical Computing | NumPy |
| Visualization | Matplotlib |
| Real-Time Streaming | Apache Kafka |
| Dashboard | Streamlit |
| Development Environment | VS Code, Jupyter Notebook |

---

## 📁 Project Structure

```text
FNS-IDS/
│
├── datasets/
│   ├── UNSW-NB15/
│   └── CIC-MalDroid/
│
├── notebooks/
│   ├── EDA.ipynb
│   ├── Feature_Engineering.ipynb
│   └── Model_Training.ipynb
│
├── src/
│   ├── preprocessing.py
│   ├── feature_extraction.py
│   ├── neural_model.py
│   ├── symbolic_reasoning.py
│   ├── federated_learning.py
│   ├── prediction.py
│   └── utils.py
│
├── dashboard/
│   └── app.py
│
├── screenshots/
│   ├── architecture.png
│   ├── dashboard.png
│   ├── accuracy.png
│   └── confusion_matrix.png
│
├── docs/
│   ├── thesis.pdf
│   └── presentation.pptx
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🔄 Workflow

### Step 1: Data Collection

Collect data from:

- Network Traffic
- System Logs
- Application Activities
- Device Behavior

### Step 2: Data Preprocessing

- Missing Value Handling
- Duplicate Removal
- Feature Encoding
- Data Normalization

### Step 3: Feature Extraction

Extract meaningful features from:

- Network Patterns
- System Activities
- User Behavior

### Step 4: Neural Learning

Deep Learning Models:

- DNN
- RNN
- LSTM

### Step 5: Symbolic Reasoning

Apply:

```text
IF abnormal_system_calls
AND suspicious_network_activity

THEN Attack
```

### Step 6: Neuro-Symbolic Fusion

Combine:

- Neural Predictions
- Rule-Based Logic

### Step 7: Federated Aggregation

- Local model training
- Secure parameter sharing
- FedAvg aggregation

### Step 8: Threat Detection

Output:

```text
0 → Normal

1 → Attack
```

---

## 📊 Performance Metrics

The system is evaluated using:

### Accuracy

Measures overall prediction correctness.

### Precision

Measures attack prediction quality.

### Recall

Measures attack detection capability.

### F1-Score

Balances precision and recall.

### MCC

Matthews Correlation Coefficient.

### FPR

False Positive Rate.

### FNR

False Negative Rate.

---

## 📈 Results

The proposed FNS-IDS framework demonstrates:

- Improved Accuracy
- Better Recall
- Reduced False Positives
- Enhanced Zero-Day Detection
- Explainable Threat Analysis
- Privacy Preservation

compared to traditional IDS approaches.

---

## 🛠 Installation

Clone Repository:

```bash
git clone https://github.com/your-username/FNS-IDS.git
```

Move into Project Directory:

```bash
cd FNS-IDS
```

Install Dependencies:

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Project

Train Model:

```bash
python train.py
```

Run Dashboard:

```bash
streamlit run dashboard/app.py
```

---

## 🔮 Future Enhancements

- Blockchain-Based Secure Aggregation
- Federated Reinforcement Learning
- Edge AI Optimization
- Android Device Deployment
- Real-Time Adaptive Threat Intelligence
- Explainable AI Dashboards
- Lightweight Mobile Inference Engine

---

## 🎓 Academic Information

Bachelor of Technology (B.Tech)

Computer Science and Engineering (Cyber Security)

Rajeev Gandhi Memorial College of Engineering and Technology

Batch: 2022–2026

---

## 📜 License

This project is developed for academic and research purposes.

MIT License

---

## ⭐ Acknowledgement

We sincerely thank our guide, faculty members, and the Department of CSE (Cyber Security), RGMCET, for their continuous support and guidance throughout this project.

---

## 📬 Contact

For queries, suggestions, or collaborations:

Email: himanireddy875@gmail.com

GitHub: https://github.com/Himani-N
