# compartive-analysis-for-symptom-based-disease-prediction
## 📌 Project Overview

This project presents an **Explainable AI-based comparative analysis** of Deep Learning (DL) models and Large Language Models (LLMs) for **symptom-based disease prediction**.
Dataset: https://drive.google.com/file/d/1yLTqmu8QMQFPNdrHTko0WSkXbS60ToqS/view?usp=sharing
The main objective is to develop a system that can:
- Predict possible diseases based on user-provided symptoms
- Compare the performance of different AI models
- Provide **interpretable results** using Explainable AI techniques (SHAP)

---

### 🚀 Key Features

- 🧠 **Disease Prediction System** using AI models  
- 📊 **Comparative Analysis** of DL and LLM models  
- 🔍 **Explainable AI (XAI)** integration using SHAP  
- 💬 Supports **symptom-based input (structured + text)**  
- 📈 Evaluation using standard metrics (Accuracy, Precision, Recall, F1-score)

---

### 🤖 Models Used

#### 🔹 Deep Learning Models
- Multilayer Perceptron (MLP)
- TabNet
- Residual MLP

#### 🔹 Large Language Models (LLMs)
- XLM-RoBERTa
- ERNIE
- ELECTRA
- Xlnet

#### 🔹 Hybrid Models
- XLNet + ELECTRA
- XLM-RoBERTa + ERNIE
- ELECTRA + ERNIE

---

### 📊 Results Summary

- Deep Learning models slightly outperformed LLM models on structured data
- MLP achieved the highest accuracy (~86.7%)
- ELECTRA performed best among LLMs (~85%)
- Hybrid models showed stable performance (~85%)

---

### 🧩 Technologies Used

- Python
- TensorFlow / PyTorch
- Hugging Face Transformers
- Scikit-learn
- Pandas, NumPy
- SHAP (Explainable AI)
- Matplotlib / Seaborn

---

### 🎯 Objective

To build a **reliable, accurate, and interpretable AI-based healthcare support system** that helps in early disease prediction and improves decision-making using explainable models.

---

### 📌 Use Case

This system can be used for:
- Early disease detection
- Healthcare assistance tools
- AI-based medical research
- Chatbot-based symptom analysis systems
