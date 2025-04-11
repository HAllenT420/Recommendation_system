# 🧠 End-to-End MLOps Project: Anime Recommendation System

This project is an end-to-end MLOps-powered **Anime Recommendation System** that utilizes modern ML lifecycle best practices. It covers everything from **data ingestion** and **model training** to **experiment tracking** and **CI/CD deployment** using cloud-native tools and infrastructure.

---

## 🚀 Project Workflow

Here's a complete overview of the project's modular pipeline:
📦 DATABASE SETUP └── GCP Bucket for centralized data storage

🛠️ PROJECT SETUP └── Folder structure, virtual environment, config, and requirements

⬇️ DATA INGESTION └── Selective anime-user data loading

📊 DATA PROCESSING └── Cleaning, merging, feature engineering (genre, type, popularity)

📒 JUPYTER NOTEBOOK TESTING └── EDA, sanity checks, quick validations

🧠 MODEL ARCHITECTURE └── Built models for classification and regression (collab + content)

🏋️ MODEL TRAINING └── Trained base models using clean data and tuned parameters

🔗 EXPERIMENT TRACKING └── Used Comet-ML for tracking metrics and parameters

🧪 TRAINING PIPELINE └── Created modular training pipeline scripts

📦 DATA AND CODE VERSIONING ├── Data versioned using DVC and stored on GCP Buckets └── Code versioned with Git and GitHub

🧩 PREDICTION HELPERS └── Custom inference helpers and input transformers

🧾 USER APP WITH PREDICTION PIPELINE └── Final user-facing app (Streamlit / Flask compatible)

🚢 CI/CD DEPLOYMENT (Jenkins + Kubernetes + GCP) ├── Jenkins for automation ├── Docker for containerization ├── GCR for Docker image storage └── Kubernetes on GCP for deployment and scaling


---

## 📦 Tech Stack

### Languages & Libraries
- **Python**, Pandas, NumPy, Scikit-learn
- **TfidfVectorizer**, Cosine Similarity, Surprise (SVD, KNN)

### MLOps Tools
- **DVC** – Data Version Control
- **Git + GitHub** – Code versioning
- **Comet-ML** – Experiment Tracking
- **Docker + GCR** – Containerization & Image Registry
- **Jenkins** – Continuous Integration
- **Kubernetes on GCP** – Scalable deployment

🧑‍💻 Author
Allen Tider Harry
📧 allentider@gmail.com


Credits:
DataGuru & Krish Naik



