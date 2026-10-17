# 🩺 Fetal Health Analysis Using Machine Learning


**Try the application:** https://fetal-health-analysis.onrender.com

**GitHub Repository:** https://github.com/Thurkapally-Rohan/Fetal-Health-Analysis

---

## 📌 Project Overview

Fetal Health Analysis is a machine-learning web application designed to analyze Cardiotocography (CTG) data and predict fetal health categories.

The application accepts **21 CTG input features** and uses a trained machine-learning model to classify the input into one of three categories:

- 🟢 **Normal**
- 🟡 **Suspect**
- 🔴 **Pathological**

The project demonstrates how machine learning can be integrated with a web application to make model predictions accessible through a user-friendly interface.

## ✨ Key Features

- **Fetal Health Prediction:** Predicts a fetal health category from CTG features.
- **21 Input Features:** Accepts the CTG parameters required by the trained model.
- **Interactive Web Interface:** Provides a convenient interface for entering data and viewing predictions.
- **Data Visualization:** Includes visualizations to explore fetal health and model-related results.
- **PDF Report Generation:** Generates downloadable prediction reports.
- **Multilingual Interface:** Supports English, Telugu, Hindi, and Tamil, where available in the application.
- **Machine Learning Integration:** Uses a trained model and a scaler for processing input data.
- **Online Deployment:** Hosted on Render for public access.

## 🛠️ Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Flask | Web application and routing |
| Scikit-learn | Machine-learning tools |
| XGBoost | Machine-learning model support |
| NumPy | Numerical computations |
| Pandas | Data processing |
| Joblib | Loading saved model artifacts |
| Matplotlib | Data visualization |
| ReportLab | PDF report generation |
| HTML/CSS | Web interface |
| Git & GitHub | Version control and source code hosting |
| Render | Web application deployment |

## ⚙️ How It Works

1. The user opens the web application.
2. The user enters the required 21 CTG feature values.
3. The application processes the input using the saved preprocessing scaler.
4. The trained machine-learning model generates a prediction.
5. The predicted category is displayed in the interface.
6. The user can explore available visualizations and generate a PDF report.

## 💻 Run the Project Locally

### Prerequisites

- Python 3.x
- Git
- pip

### 1. Clone the repository

```bash
git clone https://github.com/Thurkapally-Rohan/Fetal-Health-Analysis.git
```

### 2. Navigate to the project directory

```bash
cd Fetal-Health-Analysis/Fetal-Health-Prediction-master
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Start the application

```bash
python app.py
```

### 5. Open the application

Visit the following address in your browser:

```text
http://127.0.0.1:5000
```

## 📂 Project Structure

```text
Fetal-Health-Analysis/
└── Fetal-Health-Prediction-master/
    ├── app.py
    ├── requirements.txt
    ├── fetal_health_model.pkl
    ├── scaler.pkl
    ├── train_model.py
    ├── visualize_models.py
    ├── templates/
    │   ├── index.html
    │   └── visualizations.html
    ├── static/
    ├── fonts/
    └── data/
```

*Note: The files and folders shown above represent the main project structure; additional files may also be present.*

## 🎯 Learning Outcomes

Through this project, I gained practical experience in:

- Integrating machine-learning models with a Flask web application.
- Processing numerical input data for model prediction.
- Working with Python data science libraries.
- Building web interfaces using HTML and CSS.
- Generating PDF reports programmatically.
- Managing project files using Git and GitHub.
- Deploying a Python application to a cloud hosting platform.

## 🔮 Future Improvements

- Improve prediction performance through model evaluation and tuning.
- Add more interactive charts and data exploration features.
- Enhance input validation and error handling.
- Improve accessibility and responsive design.
- Add automated testing and deployment workflows.

## ⚠️ Disclaimer

This project is intended for **educational and research purposes only**. Its predictions must not be used as a substitute for professional medical advice, diagnosis, or clinical decision-making. Real-world fetal health assessment must be performed by qualified healthcare professionals using validated clinical methods.

## 👨‍💻 Developer

**Thurkapally Rohan**

B.Tech — Electronics and Computer Engineering (ECM)

- **GitHub:** https://github.com/Thurkapally-Rohan
- **Project Repository:** https://github.com/Thurkapally-Rohan/Fetal-Health-Analysis
- **Live Application:** https://fetal-health-analysis.onrender.com

---

⭐ If you find this project interesting, consider starring the repository!
