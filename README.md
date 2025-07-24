# 🩺 Mega Health Recommendation System

A smart health assistant built using **Streamlit**, **Google Gemini AI**, and **machine learning** to provide personalized health insights based on uploaded reports.

## 🚀 Features

- Upload and analyze health reports in **PDF**, **image**, **Excel**, or **CSV** formats.
- Extract insights and suggestions from medical images using **Gemini Vision AI**.
- Provide personalized recommendations using symptoms or health vitals.
- Risk prediction using **RandomForestClassifier**.
- Interactive charts for metrics like BMI, Blood Pressure, Glucose, etc.
- Chatbot for real-time health advice powered by **Gemini**.

## 🧰 Technologies Used

- Python, Streamlit
- Pandas, NumPy, scikit-learn
- Plotly for visualization
- PyMuPDF for PDF parsing
- Google Generative AI (Gemini) API

## 📂 How to Run

1. Clone the repo or download the files.
2. Install dependencies:

```bash
pip install -r healthapp_requirements.txt
```

3. Run the app:

```bash
streamlit run healthapp.py
```

## 📌 Input Formats Supported

- `.pdf`, `.png`, `.jpg`, `.jpeg`
- `.csv`, `.xlsx`

## 🔐 Note

You must have a valid **Google Generative AI API Key** and store it in `st.secrets["GOOGLE_API_KEY"]`.

---

Developed as part of an AI health recommendation internship project.
