# Machine Learning Based Detection of DDoS Attacks  
### Approaches, Challenges and Solutions

## Overview
This project presents an intelligent and scalable DDoS Attack Detection and Mitigation Framework that leverages Machine Learning and Software Defined Networking (SDN) to identify and control malicious network traffic in real time.

The system evaluates multiple supervised ML algorithms to classify network traffic as benign or malicious while integrating adaptive mitigation strategies such as dynamic rate limiting and intelligent load balancing to maintain service availability during attacks.

---

## Key Features
- Real-time DDoS attack detection
- Comparative evaluation of 5 ML algorithms
- Dynamic rate limiting for malicious traffic
- Intelligent load balancing mechanism
- Live traffic monitoring dashboard
- SDN-integrated adaptive security framework
- High accuracy with low false positives
- Scalable architecture for Cloud and IoT environments

---

## Machine Learning Models Used
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Decision Tree Classifier
- Random Forest Classifier
- Gradient Boosting Classifier

---

## System Architecture
The framework operates in multiple layers:

### 1. Traffic Monitoring Layer
Captures incoming network traffic flows.

### 2. Data Processing Layer
Performs cleaning, preprocessing, normalization, and feature extraction.

### 3. Machine Learning Layer
Classifies traffic as legitimate or malicious.

### 4. Mitigation Layer
Applies dynamic rate limiting and intelligent load balancing.

### 5. Monitoring & Control Dashboard
Provides live visualization, alerts, and traffic analytics.

---

## Novelty of the Project
The proposed framework introduces a smart and adaptive DDoS defense system by comparatively evaluating five machine learning algorithms under identical network conditions to identify the most efficient detection model. Unlike traditional systems focused only on attack detection, the framework integrates automated mitigation techniques such as dynamic rate limiting and intelligent load balancing to ensure uninterrupted service availability and scalable real-time protection.

---

## Tech Stack

### Backend
- Python
- Flask
- Scikit-learn
- Pandas
- NumPy

### Frontend
- HTML
- CSS
- JavaScript

### Database
- MySQL

### Monitoring & Visualization
- Grafana
- Prometheus
- SIEM Integration

---

## Dataset
The project uses labeled network traffic datasets containing:
- Benign Traffic
- UDP Flood Attacks
- Smurf Attacks

Features include:
- Packet count
- Byte count
- Flow duration
- Packet rate
- Protocol type
- Traffic behavior statistics

---

## Performance Metrics
The models are evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- False Positive Rate

The Decision Tree Classifier achieved the best overall performance with high detection accuracy and low inference latency.

---

## Installation & Setup

### Clone Repository
```bash
git clone https://github.com/your-username/ddos-detection-system.git
cd ddos-detection-system
```

### Install Dependencies
```bash
pip install -r requirements.txt
```

### Run Application
```bash
python app.py
```

---

## Future Enhancements
- Federated Learning Integration
- Blockchain-based attack logging
- Real-time cloud deployment
- Deep Learning based detection models
- Adversarial attack resistance
- Edge and IoT optimized deployment

---

## Applications
- Enterprise Network Security
- Cloud Infrastructure Protection
- Smart City Networks
- IoT Security
- Financial and Banking Systems
- Healthcare Infrastructure

---

## Authors
- Arjun Chadda
- Kshitij Rathee

---

## License
This project is developed for academic and research purposes under SRM Institute of Science and Technology.
