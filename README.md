
# 🚀 AI Coder Studio

### *AI-Powered Web IDE built using Base44 (No Backend, 100% Cloud-Native)*

**Live App:** [https://ai-coder-studio-4578c246.base44.app](https://ai-coder-studio-4578c246.base44.app)

**Workspace:** [https://app.base44.com/apps/690e0a50ab3255f04578c246/editor/preview/landing](https://app.base44.com/apps/690e0a50ab3255f04578c246/editor/preview/landing)

AI Coder Studio is a **full-featured AI-powered Web IDE** built entirely using **Base44’s frontend, data entities, and LLM integrations** — without writing any backend or custom serverless functions.

This project demonstrates how a complete AI coding environment can be created using Base44’s capabilities alone.

---

## ✨ Features

### 🧠 AI Code Assistant

* Natural language → code generation
* Code explanation, debugging suggestions
* Inline code improvement
* Works through Base44’s InvokeLLM engine

### 📝 Code Editor

* Monaco-style editor (custom built using Base44 components)
* Syntax-friendly UI
* Line numbers & clean monospace interface
* Multi-file support

### 📁 Project Management

* Create / Delete / Rename files
* Save entire projects
* Load existing projects
* Export code

### 👁️ Live Preview (Static)

* Preview HTML/CSS/JS output instantly
* Safe sandboxed preview using iframe

### 💬 AI Chat Panel

* Full conversation history
* Ask coding questions, request fixes
* Store chats for future reference

### ⚙️ Settings Page

* User preferences
* Code theme
* Editor configuration

---

## 📦 Project Structure

```
/src
  /pages
    landing
    editor
    projects
    ai-assistant
    settings
  /components
    FileExplorer
    CodeEditor
    PreviewPane
    ChatPanel
  /entities
    Project
    ChatMessage
    CodeSnippet
```

Built using **only Base44 pages, components, entities, and AI actions**.

---

## 🛠️ Tech Stack

* **Base44** – Frontend, data entities, and AI integration
* **InvokeLLM** – Code generation & debugging
* **React (Base44 internal)**
* **Browser Preview (iframe)**
* **File Storage via Base44 Entities**

> ⚠ No backend, no APIs, no external services.
> All functionality implemented within Base44’s ecosystem.

---

## 🚀 How It Works

### 1. AI Code Generation

The AI Assistant sends prompts to Base44’s built-in LLM.
Returns:

* Functions
* Components
* Full code files
* Fix suggestions

### 2. Project Storage

Each project saves:

* Name
* File tree
* Content
* Last modified timestamp

### 3. Live Preview

For HTML/CSS/JS projects, the preview pane renders output instantly.

---

## 📚 Entities

### **Project**

Stores multiple files with path + content.

### **ChatMessage**

Stores full conversation with AI.

### **CodeSnippet**

Reusable code patterns.

---

## 🎯 Why This Project?

The goal was to test:
✔ How far a full IDE can be built using *only* Base44
✔ AI-assisted coding without backend logic
✔ Real-world multi-file development inside a no-backend environment
✔ Seamless UI + AI workflow

---

## 🖥️ Pages Overview

### **Landing Page**

* Intro to the project
* Quick start section

### **Editor**

* Code editor
* File tree
* Live preview

### **Projects Page**

* Save, load, create new projects

### **AI Assistant**

* Chat-based code generation + debugging

### **Settings**

* Editor preferences

---

## 🧪 Future Enhancements

* GitHub integration
* Dark mode themes
* AI Autocomplete
* Component templates library
* Export project as ZIP

---

## 🙌 Author

**Sathya Seelan**
AI Engineer | Full Stack Developer | ML/DL/GenAI

---
Just tell me!
