

---

# 🍽️ **Restaurant Name Generator using LangChain & Streamlit**

![Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python\&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-App-FF4B4B?logo=streamlit\&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-AI%20Framework-green?logo=chainlink\&logoColor=white)
![Gemini](https://img.shields.io/badge/Google-Gemini-blue?logo=google)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Status](https://img.shields.io/badge/Project-Active-brightgreen)
![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-orange)


This is a fun AI-powered Streamlit app that generates fancy restaurant names and menu items based on the cuisine you choose!
Built using **LangChain**, **Google Gemini**, and **Streamlit**.

---

## 🚀 Features

* Select from popular cuisines like **Indian, Italian, Mexican, Arabic, American**, etc.
* AI generates a **unique restaurant name**.
* Automatically suggests **relevant menu items**.
* Fast, clean, user-friendly Streamlit UI.

---

## 🧠 Tech Stack

* **LangChain**
* **Google Gemini API**
* **Streamlit**
* **Python 3.8+**

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/restaurant-name-generator.git
cd restaurant-name-generator
```

### 2. Create and Activate Virtual Environment

```bash
python -m venv venv
source venv/bin/activate     # Mac/Linux
venv\Scripts\activate        # Windows
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

Create a file named **`secret_key.py`** and add your key:

```python
openapi_key = "your-openai-api-key"
```

---

## 🧪 Run the App

```bash
streamlit run main.py
```

---

## 📂 Project Structure

```
restaurant-name-generator/
│
├── main.py                 # Streamlit app
├── langchain_helper.py     # LangChain logic
├── secret_key.py           # API keys (ignored from Git)
├── requirements.txt        # Dependencies
└── README.md               # Documentation
```

---

## ⚠️ Important Notes

* **Never upload API keys** or `secret_key.py` to GitHub.
* Ensure your **Gemini/OpenAI API quota** is active before running the app.

---

## ✨ Future Improvements

* Add **Gemini 2.0 / GPT-4o** support
* Add UI Themes / Custom CSS
* Deploy on **Streamlit Cloud** / **HuggingFace Spaces**

---


