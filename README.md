
# 🧠 Student Performance Estimator

This project is a **Flask-based web application** that predicts student performance based on daily study hours using a trained **machine learning regression model**. Users can input study hours through a simple web form, and the model returns the expected percentage of marks.

---

## 🚀 Project Overview

- 🎯 **Goal:** Estimate a student's score based on the number of hours they study per day.
- 🧪 **Model:** Trained using supervised learning (regression) on historical student data.
- 🌐 **Interface:** Flask web app with HTML form for input and results display.
- 📊 **Persistence:** Each prediction (input + output) is logged and saved to a CSV file (`smp_data_from_app.csv`) for future analysis.

---

## 🛠️ Technologies Used

- **Python 3**
- **Flask** – Lightweight web framework
- **NumPy & Pandas** – Data manipulation
- **Scikit-learn** – Machine Learning library
- **Joblib** – For loading the saved model
- **HTML/CSS** – Frontend via Jinja templates

---

## 🧪 Model Training Highlights (`student_marks.ipynb`)

- Imported dataset with study hours and marks.
- Cleaned and prepared the data.
- Trained a **Linear Regression** model.
- Evaluated performance using R² score and MAE.
- Saved the model using `joblib` for integration with Flask.

---

## 💻 Running the Application

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/student-performance-predictor.git
   cd student-performance-predictor
   ```

2. **Install dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Ensure the trained model file is available**
   > Place `Student_Performance_Estimator.pkl` in the root directory next to `app.py`.

4. **Run the Flask application**
   ```bash
   python app.py
   ```

5. **Open your browser**
   Navigate to: [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 📦 Future Enhancements

- 🌍 Deploy the application on platforms like **Heroku** or **Render**
- 📊 Add charts/visuals for recent predictions
- 📈 Add more features such as sleep hours, attendance, etc.
- 🔌 Expose a **REST API** for programmatic access

---

## Thank You
