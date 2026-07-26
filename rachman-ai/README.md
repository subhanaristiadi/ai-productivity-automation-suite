# 🤖 RACHMAN AI

An AI-powered multimodal Telegram assistant built with **n8n**, **Large Language Models (LLMs)**, and **OpenAI-Compatible APIs**.

RACHMAN AI allows users to interact naturally through text, images, documents, and voice messages, while integrating seamlessly with Google Workspace for productivity and knowledge management.

---

# ✨ Features

## 💬 AI Chat Assistant

Ask questions about:

- Programming
- AI & Machine Learning
- n8n Workflow Automation
- Data Analysis
- Writing
- Research
- Productivity
- General Knowledge

---

## 🖼 Image Analysis

Analyze images directly from Telegram.

Examples:

- Screenshots
- Workflow diagrams
- Charts
- Documents
- UI designs
- Error messages
- Source code

---

## 📄 PDF Analysis

Upload any PDF and ask questions such as:

- Summarize this document
- Explain chapter 3
- Extract important points
- Translate the document
- Find specific information

---

## 🎤 Voice Transcription

Send a voice message.

RACHMAN AI will:

- Convert speech to text
- Understand the request
- Generate an intelligent response

---

## 🧠 Conversation Memory

Maintains short-term memory for more natural conversations.

Examples:

```
User:
My project uses n8n.

Later...

User:
How can I improve it?
```

The assistant remembers the previous context.

---

## 📝 Google Docs Logging

Every interaction can be automatically stored in Google Docs for future reference.

Useful for:

- AI conversations
- Research
- Documentation
- Personal knowledge base

---

# 🏗 Architecture

```
Telegram User
      │
      ▼
Telegram Trigger
      │
      ▼
Switch Router
      │
      ├───────────────┐
      │               │
      ▼               ▼
Text            Image/PDF/Voice
      │               │
      └──────┬────────┘
             ▼
      AI Processing
             │
             ▼
 Large Language Model
             │
             ▼
 Google Workspace
      │
      ├── Google Docs
      └── Telegram Reply
```

---

# ⚙️ Supported Inputs

| Input | Supported |
|--------|-----------|
| Text | ✅ |
| Image | ✅ |
| PDF | ✅ |
| Voice Message | ✅ |

---

# 🛠 Tech Stack

| Category | Technology |
|------------|----------------|
| Workflow | n8n |
| Messaging | Telegram Bot API |
| AI Models | Mistral, GPT, Qwen |
| AI Providers | Bynara, Groq |
| Vision | GPT Vision |
| Speech-to-Text | Whisper Large V3 Turbo |
| Memory | Buffer Memory |
| Storage | Google Docs |
| API | OpenAI Compatible |

---

# 📂 Folder Structure

```
rachman-ai/

workflow/
    RACHMAN AI.json

tutorial/
    README.md

screenshots/
    workflow.png
    telegram-chat.png
    image-analysis.png
    pdf-analysis.png
    voice-message.png

README.md
```

---

# 🚀 Example Prompts

### Chat

```
Explain Docker networking.
```

---

### Image

```
Analyze this workflow.
```

---

### PDF

```
Summarize this PDF.
```

---

### Voice

```
(Voice Message)
```

---

### Coding

```
Create an n8n workflow for Telegram automation.
```

---

# 🌟 Highlights

- Multimodal AI Assistant
- Natural Language Processing
- Image Understanding
- PDF Analysis
- Voice Transcription
- Conversation Memory
- Google Docs Integration
- Telegram Automation
- Production-ready n8n Workflow

---

# 🛣 Roadmap

- OCR Support
- YouTube Video Analysis
- Web Search Integration
- RAG Knowledge Base
- Calendar Integration
- Gmail Integration
- Google Drive Search
- Multi-user Authentication

---

# 📸 Screenshots

Coming soon.

---

# 👨‍💻 Author

**Subhan Aristiadi Rachman**

AI Automation Developer

GitHub

https://github.com/subhanaristiadi

---

# 📄 License

This project is licensed under the MIT License.
