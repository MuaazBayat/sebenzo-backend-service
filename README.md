
<p align="center">
  <img src="docs/statics/logo.png" alt="Service Logo" width="80%">
</p>

# Sebenzo Backend Service
[![Python](https://img.shields.io/badge/python-3.11%2B-blue.svg)](https://www.python.org/)
[![FastAPI](https://img.shields.io/badge/FastAPI-0.110.0-green.svg)](https://fastapi.tiangolo.com/)
[![License](https://img.shields.io/github/license/your-username/your-repo)](LICENSE)
[![Build](https://github.com/your-username/your-repo/actions/workflows/main.yml/badge.svg)](https://github.com/your-username/your-repo/actions)
[![Coverage](https://img.shields.io/codecov/c/github/your-username/your-repo)](https://codecov.io/gh/your-username/your-repo)

A modern, modular backend built with **FastAPI**, using [`uv`](https://github.com/astral-sh/uv).

---

## 🧰 Features

---

## 🚀 Quickstart

### 📦 Requirements

- Python 3.11+
- [`uv`](https://github.com/astral-sh/uv)

---

### 🛠️ Setup (with `uv`)

```bash
# Install uv if you haven't
curl -Ls https://astral.sh/uv/install.sh | sh

# Create and activate virtual environment
uv venv
source .venv/bin/activate  # or uv venv --python=3.11 && source .venv/bin/activate

# Install dependencies
uv pip install -r requirements.txt

# Run development server
uvicorn app.main:app --reload
