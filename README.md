# 🩺 Teladoc: Health Prediction System using Machine Learning

![Teladoc Banner](https://img.shields.io/badge/Status-Deployed-success?style=flat-square)  
A machine learning-powered web application that predicts potential diseases based on user-entered symptoms. Built to make preliminary health diagnostics more accessible and intuitive.

---

## 🚀 Live Demo

👉 [Visit Teladoc Web App](https://teladoc.onrender.com/home)

---

## 📌 Features

- 🧠 Machine Learning-based disease prediction  
- 📊 Symptom-to-disease inference using pre-trained model  
- 🌐 Interactive web interface for input/output  
- 📝 Confidence score or probability for predicted output  
- 💬 Health tips or description of the predicted condition  

---

## 🛠️ Tech Stack

| Layer       | Tools/Frameworks                       |
|-------------|----------------------------------------|
| Frontend    | HTML, CSS, JavaScript                  |
| Backend     | Flask / FastAPI (Python)               |
| ML Model    | Scikit-learn / Pandas / NumPy          |
| Deployment  | Render.com / Docker                    |
| Version Control | Git + GitHub                       |

---

## 🧠 ML Model Details

- **Dataset**: Symptoms vs Diseases dataset (public or custom)
- **Model**: Trained using Decision Tree / Random Forest / Naive Bayes
- **Accuracy**: ~85–95% (depending on model and training data)
- **Features**: 100+ common symptoms
- **Target**: 40+ possible disease categories

---

## 🧪 How to Run Locally

```bash
# Clone the repository
git clone https://github.com/utsav-pal/Teladoc.git
cd Teladoc

# Create virtual environment and install dependencies
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt

# Run the app
python app.py
