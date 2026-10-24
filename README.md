<div align="center">

# 📊 Employee Absence Predictor
### 🎓 CS 435 — Machine Learning Project

A Machine Learning web application designed to predict annual employee absence days based on demographic and employment attributes. Powered by a custom-trained **Gradient Boosting Regressor** and built as a lightweight, interactive web interface.

---

</div>

## 📌 Project Overview

This project provides an end-to-end Machine Learning solution for HR analytics, predicting employee absence days and classifying potential risks to optimize workplace efficiency.

```
📁 Repository Structure
.
├── 📄 README.md                              # Main project documentation
└── 📁 ML-Project-Absence_Predictor/          # Main project directory
    ├── 🌐 CS435_Absence_Predictor.html       # Web application (HTML/CSS/JS + ML model weights)
    └── 📓 ML_Model_Training.ipynb            # Jupyter Notebook used for model training and exports
```

---

## 🌟 Key Features

* ⚡ **Instant Predictions:** Powered by a lightweight, browser-side tree traversal algorithm for gradient boosting.
* 🎛️ **Interactive Inputs:** Real-time adjustments for demographics, salary, work shifts, and absence history.
* 💡 **HR Actionable Insights:** Categorizes risk levels (Low, Medium, High) with tailor-made HR recommendations.
* 🎨 **Interactive UI:** Dynamic progress gauges, custom CSS, and seamless visual feedback.

---

## 📈 Model Performance & Metrics

The machine learning model was trained on **10,000 employee records** using Gradient Boosting techniques.

| Metric | Value |
| :--- | :--- |
| **Model Algorithm** | Gradient Boosting Regressor |
| **R² Score / Accuracy** | `81.6%` |
| **Mean Absolute Error (MAE)** | `± 1.99 days` |
| **Dataset Size** | `10,000 Records` |

---

## 🛠️ Input Features

The model evaluates **11 distinct features** to generate predictions:

1. **Gender** — *(Male / Female)*
2. **Nationality** — *(Saudi, Egyptian, Indian, Pakistani, etc.)*
3. **Age** — *(Years)*
4. **Marital Status** — *(Single / Married)*
5. **Number of Children** — *(0 to 6+)*
6. **District** — *(Riyadh districts: Al Olaya, Al Malaz, Al Sahafah, etc.)*
7. **Transportation Type** — *(Car, Metro, Bus, Uber)*
8. **Job Title** — *(Software Engineer, Data Analyst, HR Specialist, etc.)*
9. **Monthly Salary** — *(in SAR)*
10. **Work Shift** — *(Morning, Evening, Rotational)*
11. **Previous Year Absence Days** — *(Historical baseline)*

---

## 💻 How to Run Locally

No back-end server or external dependencies are required to run the web interface! The entire prediction pipeline runs natively in the browser.

### 1️⃣ Clone Repository
```bash
git clone https://github.com/YOUR_USERNAME/CS435_Absence_Predictor.git
```

### 2️⃣ Run Application
1. Open the folder: `ML-Project-Absence_Predictor/`
2. Double-click `CS435_Absence_Predictor.html` to open it in any modern browser (Chrome, Safari, Firefox, Edge).

### 3️⃣ View Notebook
To inspect or modify the training model, open `ML_Model_Training.ipynb` using Jupyter Notebook, JupyterLab, or VS Code.

---

<div align="center">

**CS 435 — Machine Learning**  
*Focus: Gradient Boosting, Decision Trees, Data Preprocessing, & Model Deployment.*

</div>