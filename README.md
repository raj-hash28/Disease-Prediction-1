# 🧠 Disease Prediction Web App

A Flask-based web application that predicts diseases based on selected symptoms using a trained Random Forest model.

---

## 🚀 Features

* Predict disease based on user-selected symptoms
* Clean, responsive UI using **Tailwind CSS**
* Trained on synthetic + noisy data to avoid overfitting
* Modular folder structure for scalability
* Includes developer info and contact pages

---

## 🔧 Setup Instructions

1. **Clone the repo**:

   ```bash
   git clone https://github.com/rishabh3562/disease-predictor.git
   cd disease-predictor
   ```

2. **Create and activate virtual environment**:

   ```bash
   python -m venv venv
   source venv/bin/activate  # or venv\Scripts\activate on Windows
   ```

3. **Install dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the app**:

   ```bash
   python app.py
   ```

5. **Access it** at:

   ```
   http://127.0.0.1:5000/
   ```

---

## 📊 Model Info

* **Algorithm**: Random Forest Classifier
* **Input**: One-hot encoded symptom vector
* **Accuracy**: Tuned down from 98% → 68% with synthetic noise for realism

---

## 👨‍💻 Developer

* **Name**: Rishabh Dubey
* **Tech Stack**: Python, Flask, Tailwind CSS
* **GitHub**: [github.com/rishabh3562](https://github.com/rishabh3562)
* **Email**: [dubeyrishabh108@gmail.com](mailto:dubeyrishabh108@gmail.com)

---

## 📬 Contact

reach out via email above.

---

## 📄 License

This project is licensed under the MIT License.
