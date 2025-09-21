# 🫀 Heart Disease Prediction Project  

## 📌 Project Overview  
This project predicts the likelihood of heart disease using **machine learning techniques**.  
It includes:  
- Data preprocessing & cleaning  
- Dimensionality reduction (PCA)  
- Feature selection  
- Supervised & unsupervised learning models  
- Hyperparameter tuning  
- Streamlit UI for deployment  

---

## 📂 Repository Structure  
```
Heart_Disease_Project/
│── data/                # Dataset (cleaned and processed)
│── scripts/             # Data preprocessing scripts
│── models/              # Trained models in .pkl format
│── notebooks/           # Step-by-step Jupyter Notebooks
│── results/             # Evaluation metrics & results
│── streamlit_app.py     # Streamlit UI source code
│── requirements.txt     # Dependencies
│── README.md            # Project Documentation
```

---

## ⚙️ Installation & Setup  

1. **Clone the repository**  
```bash
git clone https://github.com/YourUsername/Heart_Disease_Project.git
cd Heart_Disease_Project
```

2. **Install dependencies**  
```bash
pip install -r requirements.txt
```

3. **Run Jupyter Notebooks (Optional)**  
```bash
jupyter notebook notebooks/
```

---

## 🚀 Running the Streamlit App  

1. Run the app locally:  
```bash
streamlit run streamlit_app.py
```

2. Open your browser at:  
```
http://localhost:8501
```

---

## 🌍 Deployment with Ngrok  

If you want to share the app online without deploying to cloud:  

1. Install Ngrok:  
```bash
pip install pyngrok
```

2. Run the app:  
```bash
streamlit run streamlit_app.py
```

3. In another terminal, run:  
```bash
ngrok http 8501
```

4. Copy the **Forwarding URL** (e.g., `https://xxxx.ngrok.io`) and share it.  

---

## ✅ Deliverables  
✔️ Cleaned dataset with selected features  
✔️ PCA analysis results  
✔️ Supervised & unsupervised models  
✔️ Performance evaluation metrics  
✔️ Hyperparameter optimized model  
✔️ Saved model in `.pkl` format  
✔️ Streamlit UI app  
✔️ Documentation & deployment steps  
