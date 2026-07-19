<p align="center">
  <img src="assets/banner.png" alt="AI Productivity Automation Suite Banner" width="100%">
</p>

# 🤖 AI Productivity Automation Suite

An AI-powered collection of Telegram bots built with **n8n**, **Large Language Models (LLMs)**, **Telegram Bot API**, and **Google Sheets** to automate daily productivity tasks.

This project demonstrates how AI can extract structured information from natural language and integrate it into real-world automation workflows.

---

## ✨ Features

This repository contains three AI-powered Telegram bots.

### 🏦 Finance Bot

Record income and expenses through Telegram.

Example:

```
Buy coffee 25k
```

Automatically extracts:

- Transaction type
- Amount
- Description
- Category

and stores the data in Google Sheets.

---

### 📅 Daily Activity Bot

Record daily work activities using natural language.

Example:

```
Team meeting today 09:00-11:00
```

Automatically extracts:

- Activity
- Date
- Start time
- End time

and stores the data in Google Sheets.

---

### 📚 English Vocabulary Bot

Save difficult English words while learning.

Example:

```
ubiquitous
```

Automatically stores:

- Word
- Indonesian translation
- Example sentence

---

## 🏗 System Architecture

```
Telegram
    │
    ▼
Telegram Trigger
    │
    ▼
Information Extractor
    │
    ▼
LLM
(Bynara / Groq)
    │
    ▼
Google Sheets
    │
    ▼
Telegram Reply
```

---

## 🛠 Tech Stack

- n8n
- Telegram Bot API
- Google Sheets API
- Docker
- ngrok
- Large Language Models (LLMs)
- Bynara AI Router
- Groq
- OpenAI-Compatible API
- Prompt Engineering
- Workflow Automation

---

## 📂 Repository Structure

```
ai-productivity-automation-suite/

├── finance-bot/
├── daily-activity-bot/
├── english-vocabulary-bot/
├── assets/
├── README.md
└── LICENSE
```

---

## 📦 Bots Included

| Bot | Description |
|------|-------------|
| Finance Bot | Personal income & expense tracker |
| Daily Activity Bot | AI-powered work activity logger |
| English Vocabulary Bot | AI vocabulary collector |

---

## 🚀 Future Improvements

- Dashboard with Looker Studio
- OCR support for receipts
- Voice message support
- Multi-language support
- Cloud deployment
- Database integration
- Web dashboard
- Monthly AI-generated reports

---

## 👨‍💻 Author

**Subhan Aristiadi Rachman**

GitHub:
https://github.com/subhanaristiadi

---

## 📄 License

This project is licensed under the MIT License.
