\---



\## 📊 Data Monitoring



\### Data Drift Monitoring

!\[Data Drift](https://github.com/Chandru-21/MLOps\_Project/assets/64595758/af0df23d-9980-4ee4-94c0-ddebdb923237)



\### Data Quality Checks

!\[Data Quality](https://github.com/Chandru-21/MLOps\_Project/assets/64595758/c1c62d64-9b69-4ca7-ba45-45ae226a7620)



\---



\## 📡 Continuous Monitoring (CM)



\### Exposing `/metrics` on FastAPI for Prometheus

!\[FastAPI Metrics](https://github.com/Chandru-21/MLOps\_Project/assets/64595758/09b18b44-8cb1-4a86-9172-c79082cb77c8)



\### FastAPI Integrated into Prometheus

!\[FastAPI Prometheus](https://github.com/Chandru-21/MLOps\_Project/assets/64595758/4b21c089-bef3-4e39-b5e1-04cb8e026345)



\### Monitoring FastAPI Methods on Grafana

!\[Grafana FastAPI](https://github.com/Chandru-21/MLOps\_Project/assets/64595758/930f0a9a-352f-41f9-8106-9b6735af8ce4)



\### Monitoring Kubernetes Cluster Resources on Grafana

!\[Grafana Kubernetes](https://github.com/Chandru-21/MLOps\_Project/assets/64595758/d046d9f9-1477-4975-9041-f4aa128bb0f3)



\---



\## 🛠️ Tech Stack



\### Infrastructure \& Cloud

| Tool | Purpose |

|------|---------|

| AWS EKS | Kubernetes cluster for model deployment |

| AWS ECR | Docker image registry |

| AWS S3 | DVC remote storage for data versioning |



\### MLOps Tools

| Tool | Purpose |

|------|---------|

| DVC | Data and model versioning |

| MLflow | Experiment tracking and model registry |

| FastAPI | Model serving REST API |

| Streamlit | Drift monitoring dashboard |



\### CI/CD \& Monitoring

| Tool | Purpose |

|------|---------|

| GitHub Actions | CI/CD automation |

| Prometheus | Metrics collection |

| Grafana | Metrics visualization |

| Pytest | Automated testing |

| Docker | Containerization |



\---



\## 🚀 Getting Started



\### Prerequisites

\- AWS Account with EKS and ECR access

\- Python 3.9+

\- Docker

\- kubectl + eksctl

\- DVC



\### Step 1 — Clone Repository

```bash

git clone https://github.com/Shubhamharanale7/MLOps-Project-Pipeline.git

cd MLOps-Project-Pipeline

```



\### Step 2 — Install Dependencies

```bash

pip install -r requirements.txt

```



\### Step 3 — Initialize DVC

```bash

dvc init

dvc remote add -d myremote s3://your-bucket-name/path

```



\### Step 4 — Run Locally

```bash

uvicorn app:app --reload

```



\### Step 5 — Run Tests

```bash

pytest

```



\---



\## 🗺️ Future Roadmap



\- \[ ] Add feature store integration (Feast)

\- \[ ] Implement A/B testing for model versions

\- \[ ] Add automated model retraining triggers on drift detection

\- \[ ] Multi-region EKS deployment

\- \[ ] Add SHAP explainability dashboard



\---



\## 📜 License



MIT License — feel free to use, modify, and distribute.



\---



\## 🙌 Contact



\*\*Shubham Haranale\*\*



📩 \[LinkedIn](https://www.linkedin.com/in/shubhamharanale7)

📧 shubhaminfosoft7@gmail.com

🐙 \[GitHub](https://github.com/Shubhamharanale7)



> If you found this helpful, consider ⭐ starring the repo and sharing it!

