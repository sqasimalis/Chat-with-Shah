# 🤖 Chatbot - Chat with Shah

A simple and interactive chatbot powered by Phidata and Groq that allows users to ask natural language questions about myself based on structured data provided in a CSV file.

---

## 🚀 Features

- Natural language interface to query structured personal data
- Markdown-formatted responses
- Auto-installs dependencies
- Uses Groq's DeepSeek LLaMA 70B model via the Phidata framework
- Built with Streamlit for a sleek UI

---

## 🧠 Technologies Used

- Streamlit – Web app framework
- Phi – Agent framework for natural language tasks
- Groq API – LLM hosting platform
- Python – Main programming language

---

## 📁 Files Overview

- **`.env`** – Add your Groq API key here:
  ```bash
  GROQ_API_KEY="your_groq_api_key"
  ```
- **`Shah-Data.csv`** – Structured dataset containing:
  | Category | Subcategory | Detail |
  |----------|----------|----------|
  | Experience | Job Title | Python Developer |
  | ... | ... | ... |
- **`app.py`** – Main application logic:
  Loads .env variables
  Configures PythonAgent with Groq and CsvFile
  Launches Streamlit interface
  Handles user queries and displays markdown-formatted answers

---

## 🛠️ Setup Instructions
1. Clone the Repo
  ```bash
  git clone https://github.com/sqasimalis/Chat-with-Shah.git
  cd chat-with-shah
  ```
2. Create .env File
  Add your Groq API Key:
  ```bash
  echo 'GROQ_API_KEY="your_groq_api_key"' > .env
  ```
3. Install Dependencies
  It’s recommended to use a virtual environment. If requirements.txt isn't present, just run the app and it will auto-install missing packages via pip_install=True.
  ```bash
  pip install -r requirements.txt
  ```
  
4. Run the App
  ```bash
  streamlit run app.py
  ```

---

## 💬 Example Queries
- What is Syed Qasim Ali Shah's job title?
- What certifications does he have?
- Tell me about his projects.

---

## 👨‍💻 Author
Syed Qasim Ali Shah
Built using modern AI tools to showcase structured self-information in an interactive way.
