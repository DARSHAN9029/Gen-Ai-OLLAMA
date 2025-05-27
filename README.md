# Langchain Demo With Gemma Model

This is a simple web app built with **Streamlit** that leverages **Langchain** and the **Ollama Gemma (Llama2) model** to create a helpful AI assistant. The app takes user questions as input and responds using the Gen AI model.

---

## Features

- Interactive question-answering using Langchain prompt templates.
- Powered by Ollama's Gemma LLM (2 billion parameters).
- Simple, clean UI built with Streamlit.
- Integrated with Langchain's prompt chaining and output parsing.
- Environment variable support using `.env`.

---

## Requirements

- Python 3.8+
- [Streamlit](https://streamlit.io/)
- [Langchain](https://github.com/hwchase17/langchain)
- [langchain_community](https://github.com/langchain-community/langchain-extensions)
- Ollama API access
- dotenv

---

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/DARSHAN9029/Gen-Ai-OLLAMA.git
   cd langchain-gemma-demo
   ```
---

Create and activate a virtual environment (optional but recommended):

```bash
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

Install the required dependencies:
```bash
pip install -r requirements.txt
```
---
Run the Streamlit app with:

```bash
streamlit run app.py
```
The app will open in your browser. Enter your question in the input box, and the Gemma LLM will generate a response.
---

License
This project is licensed under the MIT License.
---

Acknowledgments:

Langchain

Ollama

Streamlit

Feel free to contribute or open issues if you find any bugs or want new features!
