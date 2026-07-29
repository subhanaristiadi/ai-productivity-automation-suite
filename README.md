<p align="center">
  <img src="assets/banner2.png" width="100%" alt="AI Productivity Automation Suite">
</p>

# 🤖 AI Automation Portfolio

A collection of AI-powered automation projects built with **n8n**, **Telegram Bot API**, **Docker**, **Google Workspace**, and modern **Large Language Models (LLMs)**.

This repository showcases practical AI automation solutions that transform natural language into structured workflows, automate repetitive tasks, and integrate seamlessly with Google Workspace for personal productivity.

---

# 🚀 Featured Projects

## 🤖 RACHMAN AI

A multi-modal Telegram AI assistant capable of understanding text, images, PDF documents, and voice messages through intelligent workflow automation.

### Features

* 💬 AI-powered conversations
* 🖼️ Image analysis
* 📄 PDF document understanding
* 🎤 Voice transcription
* 🧠 Conversation memory
* 📚 Google Docs conversation logging
* 🤖 Telegram interface
* ⚡ Automated workflow orchestration with n8n

### AI Workflow

```text
Telegram
    │
    ▼
Message Router
    │
    ├── 💬 Text Chat
    │      ├── AI Agent
    │      ├── Conversation Memory
    │      └── Google Docs Log
    │
    ├── 🖼️ Image Analysis
    │      ├── Vision Model
    │      └── Google Docs Log
    │
    ├── 📄 PDF Analysis
    │      ├── PDF Parser
    │      ├── AI Agent
    │      └── Google Docs Log
    │
    └── 🎤 Voice Message
           ├── Speech-to-Text
           ├── AI Agent
           └── Google Docs Log

                │
                ▼

          Telegram Reply
```

### AI Stack

| Component           | Technology            |
| ------------------- | --------------------- |
| Workflow Engine     | n8n                   |
| AI Agent            | OpenAI-Compatible LLM |
| Image Understanding | Vision Model          |
| PDF Processing      | PDF Parser + LLM      |
| Speech-to-Text      | Groq Whisper          |
| Memory              | Buffer Memory         |
| Knowledge Log       | Google Docs           |
| Messaging           | Telegram Bot API      |

---

## 💰 Finance Tracker Bot

A Telegram bot that automatically records income and expenses using natural language processing and structured information extraction.

### Features

* 💵 Income & expense tracking
* 🧾 Automatic information extraction
* 🏷️ Smart transaction categorization
* 📊 Google Sheets integration
* 💬 Natural language input
* ✅ Instant Telegram confirmation

### Workflow

```text
Telegram
    │
    ▼
Telegram Trigger
    │
    ▼
Information Extractor
    │
    ▼
AI Language Model
    │
    ▼
Structured JSON
    │
    ▼
Google Sheets
    │
    ▼
Telegram Reply
```

### Example

> "Bought lunch for Rp35.000"

Automatically becomes:

* Date & Time
* Transaction Type
* Amount
* Category
* Description

---

## 📚 English Vocabulary Bot

A personal English learning assistant that automatically builds a structured vocabulary database from Telegram conversations.

### Features

* 📖 Save new vocabulary
* 🌐 Indonesian translation
* ✍️ Example sentence generation
* 📊 Google Sheets integration
* 📚 Personal vocabulary database
* 🔎 Fast vocabulary lookup

### Workflow

```text
Telegram
    │
    ▼
Telegram Trigger
    │
    ▼
Information Extractor
    │
    ▼
AI Language Model
    │
    ▼
Structured Vocabulary
    │
    ▼
Google Sheets
    │
    ▼
Telegram Reply
```

### Example

> "Serendipity"

Automatically becomes:

* Word
* Part of Speech
* Indonesian Translation
* Example Sentence
* Date Added

---

# 🛠️ Technology Stack

### Workflow Automation

* n8n
* Docker

### Artificial Intelligence

* OpenAI-Compatible LLMs
* Vision Models
* Groq Whisper

### Messaging

* Telegram Bot API

### Google Workspace

* Google Sheets
* Google Docs

### Data Processing

* Information Extractor
* Structured JSON Parsing
* PDF Processing

---

# 🧩 System Architecture

```text
                              Telegram Users
                                     │
                                     ▼
                           Telegram Bot API
                                     │
                                     ▼
                           Docker + n8n Engine
                                     │
        ┌────────────────────────────┼────────────────────────────┐
        │                            │                            │
        ▼                            ▼                            ▼

   🤖 RACHMAN AI             💰 Finance Tracker         📚 Vocabulary Bot

        │                            │                            │

   Multi-modal Router       Information Extractor     Information Extractor

        │                            │                            │

Text • Image • PDF • Voice     AI Language Model        AI Language Model

        │                            │                            │

 AI Processing Layer          Structured JSON         Structured Vocabulary

        │                            │                            │

 Memory • Google Docs         Google Sheets           Google Sheets

        │                            │                            │

        └─────────────── Telegram Response ───────────────────────┘
```

---

# 🎯 Project Goals

* Build production-ready AI assistants for personal productivity.
* Demonstrate practical AI workflow automation with n8n.
* Convert natural language into structured business data.
* Integrate modern LLMs with Telegram and Google Workspace.
* Showcase scalable automation architecture for real-world use cases.
* Create reusable AI workflow templates for future automation projects.

---

# 📂 Repository Structure

```text
AI-Automation-Portfolio/
│
├── 01-RACHMAN-AI/
│   ├── workflow/
│   ├── screenshots/
│   ├── docs/
│   └── README.md
│
├── 02-Telegram-Finance-Bot/
│   ├── workflow/
│   ├── screenshots/
│   ├── docs/
│   └── README.md
│
├── 03-English-Vocabulary-Bot/
│   ├── workflow/
│   ├── screenshots/
│   ├── docs/
│   └── README.md
│
├── assets/
│
└── README.md
```

---

# 📸 Preview

Each project includes:

* 📐 Workflow architecture diagrams
* ⚙️ Complete n8n workflow JSON
* 📖 Step-by-step setup guide
* 📷 Screenshots
* ✨ Feature overview
* 💬 Example conversations
* 📝 Documentation

---

# 📄 License

This repository is released under the **MIT License**.

---

## ⭐ About

This portfolio demonstrates practical applications of AI automation using modern Large Language Models, workflow orchestration, and Telegram-based interfaces to solve real-world productivity challenges.

The projects emphasize scalable workflow design, structured information extraction, Google Workspace integration, and production-ready AI automation built with **n8n**.

# ⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub.

It helps the project grow and motivates future development.

---

# 📄 License

Licensed under the MIT License.
