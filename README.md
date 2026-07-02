# 🛡️ LangChain PII Guardrails Agent

A secure AI customer service agent built with **LangChain**, **Groq LLM**, and **PII Middleware**. The project demonstrates how to protect sensitive customer information by automatically masking credit card numbers and redacting email addresses before displaying responses.

---

## 🚀 Features

- AI-powered customer service agent
- Built with LangChain Agents
- Uses Groq LLM for intelligent responses
- Automatic PII detection
- Masks credit card numbers
- Redacts email addresses
- Middleware-based security guardrails
- Tool calling support

---

## 🛠️ Tech Stack

- Python
- LangChain
- Groq LLM
- LangChain Middleware
- Python Dotenv

---

## 📁 Project Structure

```text
langchain-pii-guardrails/
│── guardrails.py
│── .env
│── requirements.txt
└── README.md
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/codinghub37/langchain-pii-guardrails.git
```

### Navigate to the Project

```bash
cd langchain-pii-guardrails
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

---

## 🔑 Environment Variables

Create a `.env` file and add your Groq API key:

```env
GROQ_API_KEY=your_api_key_here
```

---

## ▶️ Run the Project

```bash
python guardrails.py
```

---

## 📚 Workflow

1. Initialize the Groq LLM.
2. Create a customer information tool.
3. Configure LangChain PII Middleware.
4. Process customer queries.
5. Automatically mask credit card numbers.
6. Automatically redact email addresses.
7. Return secure AI-generated responses.

---

## 💡 Applications

- Secure AI Assistants
- Customer Support Automation
- Privacy-Preserving AI
- AI Guardrails
- Enterprise AI Security
- PII Protection


⭐ If you found this project useful, don't forget to give it a star on GitHub!
