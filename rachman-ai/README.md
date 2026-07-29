<p align="center">
  <img src="assets/banner3.png" width="100%" alt="AI Productivity Automation Suite">
</p>

# 🤖 RACHMAN AI

> An AI-powered multimodal Telegram assistant built with **n8n Workflow Automation**, **Docker**, **Telegram Bot API**, and modern **Large Language Models (LLMs)**.

RACHMAN AI is a personal AI assistant that combines conversational AI, image understanding, PDF analysis, speech recognition, and workflow automation into a single Telegram bot. The project demonstrates how multiple AI services can be orchestrated through n8n to build a practical, production-ready assistant.

---

# ✨ Features

* 💬 AI-powered conversations
* 🖼️ Image understanding
* 📄 PDF document analysis
* 🎤 Voice transcription
* 🧠 Conversation memory
* 📚 Automatic Google Docs conversation logging
* 🤖 Telegram Bot integration
* ⚡ Workflow automation with n8n
* 🔀 Automatic routing based on message type
* 📝 Context-aware responses

---

# 🏗️ System Architecture

```text
                        Telegram User
                              │
                              ▼
                     Telegram Bot API
                              │
                              ▼
                     Telegram Trigger
                              │
                              ▼
                      Message Router
                              │
      ┌───────────────┬───────────────┬───────────────┐
      │               │               │               │
      ▼               ▼               ▼               ▼

   Text Chat       Image File      PDF File      Voice Note

      │               │               │               │

      ▼               ▼               ▼               ▼

   AI Agent      Vision Model     PDF Parser    Whisper STT

      └───────────────┴───────────────┬───────────────┘
                                      │
                                      ▼

                              Conversation Memory
                                      │
                                      ▼

                              Google Docs Logger
                                      │
                                      ▼

                               Telegram Response
```

---

# ⚙️ Technology Stack

## Workflow Automation

* n8n
* Docker

## Artificial Intelligence

* OpenAI-Compatible LLM
* Vision Model
* Groq Whisper (Speech-to-Text)

## Integrations

* Telegram Bot API
* Google Docs

## Memory

* Buffer Memory

---

# 📂 Repository Structure

```text
RACHMAN-AI/
│
├── workflow/
│   └── RACHMAN AI.json
│
├── screenshots/
│
├── docs/
│
├── assets/
│
├── LICENSE
│
└── README.md
```

---

# 🔄 Workflow Overview

The workflow automatically detects the incoming message type and routes it to the appropriate processing pipeline.

## 💬 Text Messages

```text
Telegram
    │
    ▼
AI Agent
    │
Conversation Memory
    │
Google Docs Logger
    │
Telegram Reply
```

---

## 🖼️ Image Messages

```text
Telegram
    │
    ▼
Download Image
    │
Vision Analysis
    │
Google Docs Logger
    │
Telegram Reply
```

---

## 📄 PDF Documents

```text
Telegram
    │
    ▼
Download PDF
    │
PDF Parser
    │
AI Agent
    │
Google Docs Logger
    │
Telegram Reply
```

---

## 🎤 Voice Messages

```text
Telegram
    │
    ▼
Download Voice
    │
Groq Whisper
    │
AI Agent
    │
Google Docs Logger
    │
Telegram Reply
```

---

# 🧠 AI Components

| Component          | Purpose                            |
| ------------------ | ---------------------------------- |
| AI Agent           | General conversation and reasoning |
| Vision Model       | Image understanding                |
| Groq Whisper       | Speech-to-text transcription       |
| Buffer Memory      | Maintain conversation context      |
| Google Docs Logger | Store conversation history         |

---

# 📥 Supported Inputs

| Input Type              | Supported |
| ----------------------- | :-------: |
| Text Messages           |     ✅     |
| Images                  |     ✅     |
| PDF Documents           |     ✅     |
| Voice Messages          |     ✅     |
| Multi-turn Conversation |     ✅     |

---

# 📤 Outputs

Depending on the input, the bot can:

* Answer general questions
* Explain uploaded images
* Summarize PDF documents
* Answer questions about PDF content
* Convert speech into text
* Continue contextual conversations
* Store conversation history automatically

---

# 🚀 Getting Started

## Prerequisites

Before running the workflow, prepare the following:

* Docker
* n8n
* Telegram Bot Token
* OpenAI-Compatible API Key
* Groq API Key (Whisper)
* Google Cloud OAuth Credentials
* Google Docs access

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/RACHMAN-AI.git
```

### 2. Start n8n

```bash
docker compose up -d
```

### 3. Import the workflow

Import the `RACHMAN AI.json` workflow into n8n.

### 4. Configure credentials

Configure the required credentials:

* Telegram
* AI Provider
* Groq
* Google OAuth

### 5. Activate the workflow

Enable the workflow in n8n and start chatting with your Telegram bot.

---

# 🔐 Required Credentials

| Service          | Purpose                   |
| ---------------- | ------------------------- |
| Telegram Bot API | Receive and send messages |
| AI Provider      | Chat and reasoning        |
| Groq API         | Speech transcription      |
| Google OAuth     | Google Docs integration   |

---

# 📚 Conversation Logging

Every interaction is automatically stored in Google Docs.

Each log includes:

* Timestamp
* User message
* AI response

This provides a searchable conversation history for future reference.

---

# 📸 Screenshots

Recommended screenshots to include:

* Telegram conversation
* n8n workflow
* Image analysis example
* PDF analysis example
* Voice transcription example
* Google Docs conversation log

---

# 🛣️ Roadmap

* [ ] Streaming responses
* [ ] OCR improvements
* [ ] Multi-user support
* [ ] Long-term memory
* [ ] Retrieval-Augmented Generation (RAG)
* [ ] Vector database integration
* [ ] Web dashboard
* [ ] Function calling
* [ ] Knowledge base support

---

# 🤝 Contributing

Contributions, suggestions, and feature requests are welcome.

If you have ideas for improving the workflow or adding new capabilities, feel free to open an issue or submit a pull request.

---

# 📄 License

This project is licensed under the **MIT License**.

---

# 👤 Author

**Subhan Rachman**

AI Automation • Workflow Automation • Data Analytics • Open Source

If you found this project useful, consider giving it a ⭐ on GitHub.
