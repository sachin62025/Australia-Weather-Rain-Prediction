# 🌦️ Australia Weather Rain Prediction

This project predicts whether it will rain tomorrow in Australia using historical weather data. It is designed with a full MLOps pipeline including model development, deployment using Docker and Kubernetes, and automation via CircleCI.

---

## 🧠 Project Design Overview

- **Model Objective**: Predict the binary classification — *Will it rain tomorrow?*
- **Data Source**: Historical weather data of Australian cities.
- **Pipeline**:
  1. Preprocessing and training of a machine learning model.
  2. Exposing the prediction service via a Flask API.
  3. Containerizing the application using Docker.
  4. Deploying on Kubernetes.
  5. Automated testing & deployment via CircleCI.

---

## 🛠️ Technologies Used

| Area             | Technology        |
|------------------|-------------------|
| Programming Lang | Python            |
| Web Framework    | Flask             |
| ML Libraries     | scikit-learn, pandas, numpy |
| CI/CD            | CircleCI          |
| Containerization | Docker            |
| Orchestration    | Kubernetes        |
| Deployment       | YAML-based K8s manifests |
| Others           | Gunicorn, Joblib  |

---

## 📦 Installation

### 1. Clone the repo

```bash
https://github.com/sachin62025/Australia-Weather-Rain-Prediction.git
cd Australia-Weather-Rain-Prediction
```
### 2. Install dependencies
```bash
pip install -r requirements.txt
```
### 3. Run the application
```bash
python application.py
```
## 🐳 Docker Support
### Build Docker Image
```bash
docker build -t weather-rain-predictor .
````
### Run Container
```bash
docker run -p 5000:5000 weather-rain-predictor
```

