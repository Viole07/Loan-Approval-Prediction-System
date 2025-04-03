# 🏦 Loan Approval Prediction System

A smart and intuitive machine learning-based web app that predicts whether a loan will be approved based on applicant details. Built with **Flask**, styled with **Bootstrap**, and powered by a trained **scikit-learn model**.

---

## 🚀 Features

- **Loan Form Input**: Simple UI to enter all relevant loan parameters.
- **ML-Powered Predictions**: Uses a trained classification model to approve or reject.
- **Confidence Score**: Displays the model's confidence percentage.
- **Dark Mode**: User-friendly dark/light mode toggle.
- **Responsive Design**: Mobile-friendly and animated UI.

---

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, Bootstrap
- **Backend**: Flask (Python)
- **Model**: scikit-learn, joblib
- **Deployment**: Render

---

## 📦 Project Structure

```
Loan-Approval-Prediction-System/
├── csv/
│   ├── test.csv
│   └── train.csv
├── Flask/
│   ├── static/
│   │   └── style.css
│   ├── templates/
│   │   └── index.html
│   ├── app.py
├── loan_approval_model_optimized.pkl
├── loan_approval_model.pkl
├── Untitled.ipynb
├── README.md
```

---

## 💻 Setup & Installation

### 1. Clone the Repository
```bash
git clone https://github.com/Viole07/Loan-Approval-Prediction-System.git
cd Loan-Approval-Prediction-System/Flask
```

### 2. Create & Activate Virtual Environment
```bash
python -m venv venv
venv\Scripts\activate        # Windows
# OR
source venv/bin/activate     # macOS/Linux
```

### 3. Install Required Packages
```bash
pip install flask scikit-learn numpy joblib
```

### 4. Run the Flask App
```bash
python app.py
```

Navigate to: [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 📸 Screenshots

### 🟢 1. Loan Form Loaded in Browser
The home page is rendered with the loan form and dark mode toggle.

![Loan UI](screenshots/loan-ui.png)

---

### 🟣 2. Form Submitted
User fills the form with sample input and submits for prediction.

![Form Input](screenshots/form-submitted.png)

---

### ⏳ 3. Loader Animation Appears
A loading spinner shows while backend processes prediction.

![Loading Spinner](screenshots/loading.png)

---

### 🖼️ 4. Prediction Result Displayed
Loan is either Approved ✅ or Rejected ❌ with confidence score.

![Result](screenshots/prediction-result.png)

---

## 🌍 Deployment

### ✅ Recommended: Deploy to [Render](https://render.com)

1. Push your repo to GitHub
2. Sign in at [https://render.com](https://render.com)
3. Click **"New Web Service"**
4. Connect your GitHub repo
5. Configure:
   - **Environment**: Python 3.10+
   - **Build Command**: `pip install -r requirements.txt`
   - **Start Command**: `python app.py`
6. Hit Deploy 🚀

🎉 Your Flask app will be live on a public URL.

---

## 🔐 .gitignore Example
```gitignore
__pycache__/
venv/
*.pkl
.env
*.csv
.DS_Store
```

---

## 📜 License
MIT License — free to use, modify, and distribute.

---

Built with ❤️ by [@Viole07](https://github.com/Viole07)
