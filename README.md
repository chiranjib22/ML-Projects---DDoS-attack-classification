# DDoS Attack Classification Using Machine Learning

This project is a machine learning-based approach to detect and classify Distributed Denial-of-Service (DDoS) attacks. Using the CIC-IDS2017 dataset, we trained and evaluated three different models: Random Forest, Logistic Regression, and Neural Network.

## 🔍 Problem Statement

A Distributed Denial-of-Service (DDoS) attack is an attempt to disrupt the normal traffic of a network or server by overwhelming it with a flood of traffic. Detecting these attacks in real time is critical for maintaining the security and availability of online services.

## 📊 Dataset

- **Source**: [CIC-IDS2017 Dataset](https://www.unb.ca/cic/datasets/ids-2017.html)
- **Contents**: Network traffic data collected over 5 days including both benign and DDoS attack samples.

## 🛠️ Project Pipeline

1. **Data Preprocessing**
   - Cleaned and reformatted column names
   - Selected relevant features
   - Encoded labels (BENIGN = 0, DDoS = 1)
   - Removed null values

2. **Exploratory Data Analysis**
   - Visualized feature distributions
   - Checked correlation and class distribution

3. **Data Splitting**
   - Train: 70%
   - Test: 30%

4. **Model Training**
   - Random Forest
   - Logistic Regression
   - Neural Network

5. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-Score
   - AUC Score

## 📈 Results

| Model              | Accuracy | Precision | Recall  | F1-Score |
|-------------------|----------|-----------|---------|----------|
| Random Forest      | 0.9995   | 1.0000    | 0.9990  | 0.9995   |
| Logistic Regression| 0.9443   | 0.9100    | 0.9925  | 0.9495   |
| Neural Network     | 0.9768   | 0.9586    | 0.9990  | 0.9784   |

## 🧠 Key Learnings

- Random Forest showed perfect classification with AUC of 1.00.
- Neural Network and Logistic Regression also performed well with AUC ~0.99.
- Addressed class imbalance using oversampling.
- The model can be integrated into real-time network monitoring systems.

## 🔗 GitHub Repository

Feel free to explore and fork this project: [DDoS Attack Classification](https://github.com/chiranjib22/DDOS-Attack-Classification-ML)

## 👨‍💻 Contributors

- Mahfujur Rahman (1902006)
- Md Nur Alam (1902067)
- Chiranjib Chakraborty (1902059)

## 🏫 Institution

Hajee Mohammad Danesh Science and Technology University  
CSE 470 – Machine Learning and Pattern Recognition Sessional  
