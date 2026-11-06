<<<<<<< HEAD
# 💰 AI-Driven Personalized Budgeting System

> **Enhancing Household Financial Management with Artificial Intelligence**  
> Developed by: **Ian Jorryn Govender, Elisha Chetty, Amnkelwe Njomi, Nadia Naicker, Divani Padayachee, and Lindelweyizizwe Manqele**  
> 📍 Durban University of Technology, South Africa  

---

![Python Version](https://img.shields.io/badge/Python-3.10%2B-blue.svg)
![Flask](https://img.shields.io/badge/Framework-Flask-green.svg)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)
![Build Status](https://img.shields.io/badge/Build-Passing-success.svg)
![NLP Model](https://img.shields.io/badge/Model-DistilBERT-orange.svg)
![Status](https://img.shields.io/badge/Status-Active-brightgreen.svg)

---

## 🧠 Overview

Traditional budgeting tools often fail to capture the complexity of modern household finances. This project introduces an **AI-powered personalized budgeting web app** that uses **Natural Language Processing (NLP)** and **machine learning** to intelligently classify and forecast expenses.  

The system integrates **DistilBERT**, a transformer-based NLP model, with a **Flask backend** and **interactive Chart.js visualizations**, providing real-time, adaptive, and ethical financial insights for users.

---

## 🚀 Key Features

✅ **AI-Powered Expense Categorization**  
Automatically classifies user transactions into spending categories using a fine-tuned DistilBERT model.

✅ **Dynamic Budget Tracking**  
Displays real-time spending patterns and provides visual alerts when nearing or exceeding budget limits.

✅ **Predictive Expense Forecasting**  
Forecasts future spending based on historical data using hybrid rule-based and average-based models.

✅ **Multi-User Authentication**  
Secure login system with session management and password hashing via Flask.

✅ **Data Visualization Dashboard**  
Built with Chart.js for interactive graphs showing financial trends and budget health.

✅ **Responsive Design**  
Developed with Bootstrap 5 for optimal use on desktops, tablets, and mobile devices.

---

## 🏗️ System Architecture

User Input → Data Cleaning → NLP Model (DistilBERT/FinBERT) → Expense Classification
↓
Budget Rule Engine → Expense Prediction → Dashboard Visualization (Chart.js)

yaml
Copy code

### 🧩 Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | HTML5, CSS3, Bootstrap 5, JavaScript, Chart.js |
| **Backend** | Flask (Python) |
| **Database** | SQLite |
| **AI/NLP Model** | DistilBERT (via Hugging Face Transformers) |
| **Libraries** | Pandas, Scikit-learn, NumPy, Transformers |

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/yourusername/ai-budgeting-system.git
cd ai-budgeting-system
2️⃣ Create a Virtual Environment
bash
Copy code
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
3️⃣ Install Dependencies
bash
Copy code
pip install -r requirements.txt
4️⃣ Run the Flask Application
bash
Copy code
python app.py
5️⃣ Open in Your Browser
cpp
Copy code
http://127.0.0.1:5000/
📊 Model Performance
Model	Accuracy	Precision	Recall	F1-Score
DistilBERT	89%	88%	88%	88%
FinBERT	19%	6%	19%	9%

Result: DistilBERT outperformed FinBERT in classifying informal household transactions, demonstrating better generalization and real-time adaptability.

=======
# Smart-Budgeting-Application
Personal Finance Management and Smart Budgeting Web Application
>>>>>>> a3b3c86958f3789b2494925d1b294587bf182cab
