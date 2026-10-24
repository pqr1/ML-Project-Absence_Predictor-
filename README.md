# 📊 Employee Absence Predictor (CS 435 - Machine Learning)

A Machine Learning web application designed to predict annual employee absence days based on demographic and employment attributes. Powered by a custom-trained **Gradient Boosting Regressor** and built as a lightweight, interactive web interface.

---

## 🚀 Demo & Features

- **Interactive Inputs:** Adjust employee demographic data, job details, monthly salary, and historical absence days in real-time.
- **Instant Predictions:** Powered by lightweight, browser-side tree traversal algorithm for gradient boosting.
- **HR Actionable Insights:** Categorizes risk levels (Low, Medium, High) and provides tailor-made HR recommendations based on prediction outcomes.
- **Interactive UI:** Smooth UX designed with custom CSS styling, dynamic gauges, and immediate visual feedback.

---

## 📈 Model Performance & Metrics

The machine learning model was trained on **10,000 employee records** using Gradient Boosting techniques.

* **R² Score / Accuracy:** `81.6%`
* **Mean Absolute Error (MAE):** `± 1.99 days`
* **Dataset Size:** `10,000 Records`
* **Algorithm:** Gradient Boosting Regressor (Custom tree traversal implementation)

---

## 🛠️ Input Features

The model evaluates **11 distinct features** to generate predictions:

1. **Gender** *(Male / Female)*
2. **Nationality** *(Saudi, Egyptian, Indian, Pakistani, etc.)*
3. **Age** *(Years)*
4. **Marital Status** *(Single / Married)*
5. **Number of Children** *(0 to 6+)*
6. **District** *(Riyadh districts: Al Olaya, Al Malaz, Al Sahafah, etc.)*
7. **Transportation Type** *(Car, Metro, Bus, Uber)*
8. **Job Title** *(Software Engineer, Data Analyst, HR Specialist, etc.)*
9. **Monthly Salary** *(in SAR)*
10. **Work Shift** *(Morning, Evening, Rotational)*
11. **Previous Year Absence Days** *(Historical baseline)*

---

## 📂 Project Structure

.
├── CS435_Absence_Predictor.html  # Main application containing HTML/CSS/JS & embedded ML model weights
└── README.md                     # Project documentation

---

## 💻 How to Run Locally

No back-end server or external dependencies required! The entire prediction pipeline runs natively in the browser.

1. Clone or download this repository:
   ```bash
   git clone [https://github.com/YOUR_USERNAME/CS435_Absence_Predictor.git](https://github.com/YOUR_USERNAME/CS435_Absence_Predictor.git)