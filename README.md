# California Housing Prediction App 🏠

A full-stack Machine Learning project that predicts housing prices in California. This project covers the entire pipeline from model training to containerized deployment.

## 🚀 Project Overview
This application uses a **Random Forest Regressor** trained on the California Housing dataset. The model is served via a **Flask API**, containerized with **Docker**, and managed by **Kubernetes**.

## 🛠️ Tech Stack
* **Python**: Data processing and model training.
* **Scikit-Learn**: Machine learning framework.
* **Flask**: Web framework for the API.
* **Docker**: Containerization.
* **Kubernetes (Minikube)**: Orchestration and deployment.
* **Git/GitHub**: Version control.

## 📖 How to Run
1. **Activate the environment**:
   `source modelenv/Scripts/activate`
2. **Start Minikube**:
   `minikube start`
3. **Deploy to Kubernetes**:
   `kubectl apply -f service.yaml`
4. **Test the API**:
   Use `curl` to send a POST request with housing features to the `/predict` endpoint.

## 👨‍💻 Author
**Sudah**
A Statistics student and an aspiring Data Scientist/ML Engineer.