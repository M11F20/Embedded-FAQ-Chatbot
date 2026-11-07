# Embedded FAQ Chatbot

A lightweight educational chatbot that answers common **Embedded Systems** questions using curated Q&A content and natural conversation. Built with **Flask** and the **OpenAI API** for simple, local deployment.

---
## ✨ Features

* Conversational FAQ for Embedded Systems topics
* Covers ADC, microcontrollers, sensors, and communication protocols
* Clean, minimal Flask backend
* Easy to run locally for labs, demos, or study
* Extendable Q&A knowledge base

---

## 🧱 Tech Stack

* Python
* Flask
* OpenAI API
* HTML/CSS (simple frontend)

---

## 📁 Project Structure

```
embedded-faq-chatbot/
│
├── api.py              # Flask server & routes
├── faq_data.json       # Curated Embedded Q&A dataset
├── templates/
│   └── index.html      # Chat interface
├── static/
│   └── style.css
├── requirements.txt
└── README.md
```

---

## ⚙️ Setup & Run

### 1) Clone the repository

```bash
git clone <https://github.com/M11F20/Embedded-FAQ-Chatbot>
cd embedded-faq-chatbot
```

### 2) Create virtual environment

```bash
python -m venv venv
```

**Windows**

```bash
venv\Scripts\activate
```

**macOS/Linux**

```bash
source venv/bin/activate
```

### 3) Install dependencies

```bash
pip install -r requirements.txt
```

### 4) Add your OpenAI API key

Create a `.env` file in the root:

```
OPENAI_API_KEY=your_key_here
```

### 5) Run the app

```bash
python api.py
```

Open: [http://127.0.0.1:5000](http://127.0.0.1:5000)

---

## 🧠 How It Works

* User sends a question from the web UI
* Flask forwards it to the OpenAI API
* The model answers using the embedded FAQ knowledge
* Response is returned to the chat interface

---

## ➕ Add More Questions

Edit `faq_data.json` and add more Q&A pairs to expand the knowledge base.

---

## 🎯 Use Cases

* Study companion for Embedded Systems students
* Quick revision tool before exams
* Demo project for learning Flask + AI integration
* Educational lab assistant

---

## 📜 License

MIT License
