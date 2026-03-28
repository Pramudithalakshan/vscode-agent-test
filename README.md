<div align="center">

# 🎲 Soc Ops

**Social Bingo for in-person mixers — find people who match the prompts and get 5 in a row!**

[![Python 3.13+](https://img.shields.io/badge/Python-3.13%2B-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.115%2B-009688?logo=fastapi&logoColor=white)](https://fastapi.tiangolo.com/)
[![HTMX](https://img.shields.io/badge/HTMX-powered-3D72D7?logo=htmx&logoColor=white)](https://htmx.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![VS Code Copilot Lab](https://img.shields.io/badge/VS%20Code-Copilot%20Agent%20Lab-007ACC?logo=visualstudiocode&logoColor=white)](https://copilot-dev-days.github.io/agent-lab-python/)

</div>

---

## 🎯 What is Soc Ops?

Soc Ops is a **real-time Social Bingo game** designed for in-person team mixers, meetups, and icebreaker events. Each player gets a unique 5×5 bingo board filled with prompts like *"has lived in another country"* or *"can juggle"*. Mingle with the room, find people who match — and shout **BINGO!** 🎉

> **This repo is also a hands-on GitHub Copilot Agent lab** — you'll use VS Code's Agent Mode to transform the app from scratch using AI-powered workflows.

---

## ✨ Features

| Feature | Description |
|---------|-------------|
| 🎲 **Randomised Boards** | Every session gets a unique shuffled board |
| 🆓 **Free Space** | Classic centre free space included |
| ✅ **Win Detection** | Automatic detection of rows, columns & diagonals |
| 🔄 **Session Persistence** | Cookie-based sessions survive page refreshes |
| ⚡ **Instant Updates** | HTMX-powered interactions — no full page reloads |
| 📱 **Responsive** | Works on phones, tablets, and desktops |

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| **Backend** | [FastAPI](https://fastapi.tiangolo.com/) + Python 3.13 |
| **Templating** | [Jinja2](https://jinja.palletsprojects.com/) |
| **Frontend** | [HTMX](https://htmx.org/) + Custom CSS utilities |
| **Server** | [Uvicorn](https://www.uvicorn.org/) (ASGI) |
| **Package Manager** | [uv](https://docs.astral.sh/uv/) |
| **Linting** | [Ruff](https://docs.astral.sh/ruff/) |
| **Testing** | [pytest](https://pytest.org/) + [httpx](https://www.python-httpx.org/) |

---

## 🚀 Quick Start

### Prerequisites

- Python 3.13+
- [uv](https://docs.astral.sh/uv/getting-started/installation/) installed

> 💡 **Tip:** Use the included **DevContainer** for a fully pre-configured environment — no local installs needed!

### Run Locally

```bash
# 1. Clone the repo
git clone https://github.com/Pramudithalakshan/vscode-agent-test.git
cd vscode-agent-test

# 2. Install dependencies
uv sync

# 3. Start the development server
uv run uvicorn app.main:app --reload
```

Open **http://localhost:8000** in your browser and start playing! 🎮

### Run Tests & Linting

```bash
# Run tests
uv run pytest

# Lint the code
uv run ruff check .
```

---

## 📚 Lab Guide

This repo is the starting point for the **VS Code GitHub Copilot Agent Lab** — a 1-hour workshop where you'll use Agent Mode to build features, redesign the UI, and write tests.

| Part | Title | Duration |
|------|-------|---------|
| [**00**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=00-overview) | Overview & Checklist | Prereqs |
| [**01**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=01-setup) | Setup & Context Engineering | 15 min |
| [**02**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=02-design) | Design-First Frontend | 15 min |
| [**03**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=03-quiz-master) | Custom Quiz Master | 10 min |
| [**04**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=04-multi-agent) | Multi-Agent Development | 20 min |

> 📝 Lab guides are also available in the [`workshop/`](workshop/) folder for offline reading.

**Start here →** [**Part 00: Overview & Prerequisites**](https://copilot-dev-days.github.io/agent-lab-python/docs/step.html?step=00-overview)

---

## 🤝 Contributing

Contributions are welcome! Please read the [Contributing Guide](CONTRIBUTING.md) and [Code of Conduct](CODE_OF_CONDUCT.md) before submitting a pull request.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
