# Survive the Titanic 🚢

Welcome to the **Survive the Titanic** project! This project predicts the survival chances of Titanic passengers using machine learning models. It integrates data ingestion, processing, model training, and deployment into a seamless pipeline.

---

## 🚀 Technologies Used

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-2.0.3-green?logo=flask&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-6.2-red?logo=redis&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-13-blue?logo=postgresql&logoColor=white) ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-0.24-orange?logo=scikit-learn&logoColor=white) ![Prometheus](https://img.shields.io/badge/Prometheus-2.0-orange?logo=prometheus&logoColor=white) ![Grafana](https://img.shields.io/badge/Grafana-8.0-yellow?logo=grafana&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-20.10-blue?logo=docker&logoColor=white) ![Apache Airflow](https://img.shields.io/badge/Airflow-2.0-blue?logo=apache-airflow&logoColor=white)

---

## 📂 Project Structure

```
application.py          # Flask application for predictions
config/                 # Configuration files for database and paths
dags/                   # Airflow DAGs for data extraction and transformation
notebook/               # Jupyter notebooks for exploratory data analysis
pipeline/               # Training pipeline scripts
src/                    # Core source code for data processing, training, and logging
static/                 # Static files (CSS)
templates/              # HTML templates for the web app
artifacts/              # Generated models and raw data
```

---

## 🛠️ Features

- **Data Ingestion**: Extracts Titanic data from PostgreSQL and stores it in Redis.
- **Data Processing**: Handles missing values, feature engineering, and data balancing.
- **Model Training**: Trains a Random Forest model with hyperparameter tuning.
- **Web Application**: Flask-based app for survival prediction.
- **Monitoring**: Prometheus and Grafana for metrics and visualization.
- **Orchestration**: Apache Airflow for pipeline automation.

---

## 🏗️ How to Run

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd survive-the-titanic
   ```

2. **Install Dependencies**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Flask Application**:
   ```bash
   python application.py
   ```

4. **Access the Web App**:
   Open your browser and navigate to `http://localhost:5000`.

5. **Start Monitoring**:
   - Prometheus: `http://localhost:9090`
   - Grafana: `http://localhost:3000` (Default credentials: admin/admin)

---

## 📊 Example Prediction

1. Fill in the passenger details on the web form.
2. Click **Predict**.
3. View the survival prediction result.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).