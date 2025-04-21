# 🐳 DockerGenAI — Smart Dockerfile Generator using Local LLMs

Generate production-grade Dockerfiles for any programming language — instantly. This tool uses [Ollama](https://ollama.com/) with Meta’s LLaMA 3 model locally to automate Dockerfile creation based on your input.

> 💡 No internet APIs. No guesswork. Just fast, local, GenAI-powered DevOps magic.

---

## 🚀 Why Use This?

- ⚡ Save time writing Dockerfiles for different tech stacks
- 💬 Simply provide a language (like Java, Python, Node.js, etc.)
- 🔐 All processing happens locally with your own LLM — no external API calls
- 🧠 Follows Docker best practices (base image, dependencies, working directory, etc.)

---

## 🖥️ How to Run (Windows Friendly)

### 🛠 Prerequisites

- Python 3.8+
- Ollama installed locally
- LLaMA 3 model downloaded via Ollama

### 1️⃣ Install Ollama

[Download Ollama for Windows](https://ollama.com/download)

Then start the Ollama service:
```bash
ollama serve

2️⃣ Pull the LLaMA 3 model
ollama pull llama3

3️⃣ Setup Python Virtual Environment
python -m venv venv
venv\Scripts\activate

4️⃣ Install Dependencies
pip install -r requirements.txt

(requirements.txt should contain just: ollama)

5️⃣ Run the Generator

python generate_dockerfile.py

Enter the programming language: java

You’ll get a production-ready Dockerfile tailored to that language.




