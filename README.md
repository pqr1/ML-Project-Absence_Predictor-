📊 Employee Absence Predictor (CS 435 - Machine Learning)

A Machine Learning web application designed to predict annual employee absence days based on demographic and employment attributes. Powered by a custom-trained Gradient Boosting Regressor and built as a lightweight, interactive web interface.

🚀 Demo & Features

Interactive Inputs: Adjust employee demographic data, job details, monthly salary, and historical absence days in real-time.

Instant Predictions: Powered by lightweight, browser-side tree traversal algorithm for gradient boosting.

HR Actionable Insights: Categorizes risk levels (Low, Medium, High) and provides tailor-made HR recommendations based on prediction outcomes.

Interactive UI: Smooth UX designed with custom CSS styling, dynamic gauges, and immediate visual feedback.

📈 Model Performance & Metrics

The machine learning model was trained on 10,000 employee records using Gradient Boosting techniques.

R² Score / Accuracy: 81.6%

Mean Absolute Error (MAE): ± 1.99 days

Dataset Size: 10,000 Records

Algorithm: Gradient Boosting Regressor (Custom tree traversal implementation)

🛠️ Input Features

The model evaluates 11 distinct features to generate predictions:

Gender (Male / Female)

Nationality (Saudi, Egyptian, Indian, Pakistani, etc.)

Age (Years)

Marital Status (Single / Married)

Number of Children (0 to 6+)

District (Riyadh districts: Al Olaya, Al Malaz, Al Sahafah, etc.)

Transportation Type (Car, Metro, Bus, Uber)

Job Title (Software Engineer, Data Analyst, HR Specialist, etc.)

Monthly Salary (in SAR)

Work Shift (Morning, Evening, Rotational)

Previous Year Absence Days (Historical baseline)

📂 Project Structure

.
├── README.md                              # Main project documentation
└── ML-Project-Absence_Predictor/           # Main project directory
    ├── Absence_Predictor.html       # Web application (HTML/CSS/JS + ML model weights)
    └── ML_Model_Training.ipynb            # Jupyter Notebook used for model training and exports


💻 How to Run Locally

No back-end server or external dependencies are required to run the web interface! The entire prediction pipeline runs natively in the browser.

Clone or download this repository:

git clone https://github.com/YOUR_USERNAME/Absence_Predictor.git


Navigate to the project directory and open the web application:

Go to ML-Project-Absence_Predictor/

Open CS435_Absence_Predictor.html directly in any modern web browser (Chrome, Safari, Firefox, Edge).

To inspect or modify the training code, open ML_Model_Training.ipynb using Jupyter Notebook, JupyterLab, or VS Code.

🎓 Academic Context

Course: CS 435 — Machine Learning

Focus: Gradient Boosting, Decision Trees, Data Preprocessing, & Model Deployment.
