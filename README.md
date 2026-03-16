# Intelligent Enterprise Assistant 🤖

An AI-powered chatbot designed to assist employees in a large organization by answering questions related to HR policies, IT support, company events, and other organizational matters.

This chatbot is built using **Python, Flask, HTML, CSS, and JSON**.

\---

## 🚀 Features

* AI Chatbot for answering employee queries
* HR policy information support
* IT support assistance
* Document upload and summarization
* Bad language filtering
* Simple web-based chat interface

\---

## 🏗 Project Structure

```

AI-chatbot/
│
├── backend/
│   ├── app.py
│   ├── chatbot.py
│   ├── document\\\\\\\\\\\\\\\_processor.py
│   ├── badwords.py
│   └── data/
│        └── intents.json
│
├── frontend/
│   ├── templates/
│   │     └── chatbot.html
│   │
│   └── static/
│         └── style.css
│
├── uploads/
│
├── requirements.txt
│
└── README.md
```

\---

## ⚙ Technologies Used

* Python
* Flask
* HTML
* CSS
* JSON
* PyPDF2

\---

## 📥 Installation

### 1\. Clone Repository

git clone https://github.com/yourusername/AI-chatbot.git

cd AI-chatbot

\---

### 2\. Install Dependencies

pip install -r requirements.txt

\---

### 3\. Run the Application

cd backend

python app.py

\---

### 4\. Open in Browser

http://127.0.0.1:5000

\---

## 💬 Example Questions

Users can ask questions like:

* What is the leave policy?
* What are the working hours?
* How do I contact IT support?

\---

## 📄 Document Processing

Users can upload a PDF document and the chatbot will:

* Extract text from the document
* Provide a short summary of the document

\---

## 🛡 Bad Language Filter

The chatbot detects inappropriate words using a predefined dictionary and blocks them.

\---

## 🎯 Future Improvements

* Deep learning based chatbot
* Email OTP authentication (2FA)
* Voice assistant
* Database integration
* Multi-user support

\---

## 👨‍💻 Author

Developed for Smart India Hackathon (SIH) 2024
Problem ID: SIH1706



