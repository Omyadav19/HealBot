# 🤖 AI Therapist Chatbot

A therapy-style AI chatbot built using Django and Hugging Face API. It generates human-like supportive responses and summarizes them before displaying in a simple, modern chat UI.

---

## 💡 Features

- Therapist-style responses using Hugging Face API
- Summarized replies (short and clear)
- Clean and modern UI with typing animation
- Chat history saved locally
- API-based (Totally online)

---

## 🛠️ Built With

- Python + Django
- Hugging Face Inference API (Text Generation + Summarization)
- HTML, CSS, JavaScript (Frontend)
- SQLite-XAMMP server (for saving chat history)

---

## ▶️ How to Run

```bash
git clone https://github.com/yourusername/ai-therapist-chatbot.git
cd ai-therapist-chatbot

python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

pip install -r requirements.txt
python manage.py runserver
