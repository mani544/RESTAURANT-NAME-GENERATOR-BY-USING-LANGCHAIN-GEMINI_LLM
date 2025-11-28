# 🍽️ Restaurant Name Generator using LangChain & Streamlit

This is a fun AI-powered Streamlit app that generates fancy restaurant names and menu items based on the cuisine you choose! Built using **LangChain**, **Google Gemini**, and **Streamlit**.

---

## 🚀 Features

- Select from popular cuisines like Indian, Italian, Mexican, Arabic, and American.
- Generates a unique restaurant name using AI.
- Suggests menu items based on the generated restaurant name.
- Simple, clean Streamlit UI.

---

## 🧠 Tech Stack

- [LangChain](https://www.langchain.com/)
- [Gemini_API](https://gemini.google.com/app)
- [Streamlit](https://streamlit.io/)
- Python 3.8+

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/restaurant-name-generator.git
cd restaurant-name-generator
````

### 2. Create and Activate Virtual Environment

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

Create a file named `secret_key.py` in the root folder and add your OpenAI API key like this:

```python
# secret_key.py
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
├── secret_key.py           # API keys (DO NOT UPLOAD TO GITHUB)
├── requirements.txt        # Python dependencies
└── README.md               # This file
```

---



## ⚠️ Important Notes

* Never commit `secret_key.py` or your API keys to public repositories.
* This app uses OpenAI’s GPT via LangChain – make sure you have enough quota on your OpenAI account.

---

## ✨ Future Improvements

* Add Gemini/GPT-4o support.
* Style the Streamlit app with custom CSS or themes.
* Deploy on Streamlit Cloud or Hugging Face Spaces.

---

Let me know if you'd like a deployment-ready version or help turning this into a Streamlit Cloud app or GitHub Pages project.
