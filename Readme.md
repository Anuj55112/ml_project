hello

# 🎓 Student Performance Predictor

An end-to-end Machine Learning project that predicts a student's Maths score based on demographic details and academic performance indicators.

This project is built using:
- Python
- Scikit-learn
- Flask
- Pandas
- NumPy
- HTML/CSS

---

# 🚀 Features

- End-to-End Machine Learning Pipeline
- Data Ingestion and Transformation
- Model Training and Evaluation
- Prediction Pipeline
- Flask Web Application
- Beautiful Responsive UI
- Real-time Maths Score Prediction
- Prediction Output Restricted Between 0–100

---

# 📂 Project Structure

```bash
mlproject/
│
├── artifacts/
│   ├── model.pkl
│   └── preprocessor.pkl
│
├── notebook/
│
├── src/
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   └── model_trainer.py
│   │
│   ├── pipelines/
│   │   └── predict_pipeline.py
│   │
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── templates/
│   ├── index.html
│   └── home.html
│
├── app.py
├── requirements.txt
└── README.md
```

---

# 📊 Dataset Features

The model predicts the Maths score using:

- Gender
- Race/Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Reading Score
- Writing Score

---

# 🧠 Machine Learning Workflow

1. Data Ingestion
2. Data Transformation
3. Feature Engineering
4. Model Training
5. Hyperparameter Tuning
6. Model Evaluation
7. Prediction Pipeline
8. Flask Deployment

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone <your-repository-link>
cd mlproject
```

## 2️⃣ Create Virtual Environment

```bash
conda create -p venv python=3.10 -y
conda activate venv/
```

## 3️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

---

# ▶️ Run The Application

```bash
python app.py
```

Open browser:

```bash
http://127.0.0.1:5000
```

---

# 🌐 Web Application

The application contains:

- Modern Landing Page
- Prediction Form
- Real-time Score Prediction
- Responsive UI Design

---

# 📈 Model Output

The predicted Maths score is automatically restricted between:

```bash
0 to 100
```

to ensure realistic predictions.

---

# 🛠 Tech Stack

| Technology | Usage |
|------------|-------|
| Python | Backend |
| Flask | Web Framework |
| Scikit-learn | Machine Learning |
| Pandas | Data Processing |
| NumPy | Numerical Operations |
| HTML/CSS | Frontend UI |

---

# 📸 Screenshots

Add your project screenshots here.

---

# 👨‍💻 Author

Anuj Meena

---

# ⭐ Future Improvements

- Deploy on AWS/Render/Heroku
- Add Authentication
- Store Prediction History
- Add More ML Models
- Create Dashboard Analytics

---

# 📜 License

This project is created for educational and learning purposes.