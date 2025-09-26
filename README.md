# AI Test Playground

This repository is a sandbox for experimenting with **Artificial Intelligence**, using [Ollama](https://ollama.ai/) integrated with the **OpenAI Python client**.

Currently, the repository includes a Jupyter Notebook that:

- Checks if Ollama is running.
- Lists available models in Ollama.
- Runs a simple chat completion example.

---

## Requirements

Before running the tests, make sure you have:

- [Python 3.9+](https://www.python.org/downloads/)
- [Ollama](https://ollama.ai/) installed and running locally
- Python libraries:
  - `openai`
  - `requests`

Install dependencies with:

```bash
pip install openai requests
```

---

## How to Use

1- Start Ollama locally:
```bash
ollama serve
```

2- Open the Jupyter Notebook included in this repository.
3- Run the notebook cells to:
    - Confirm the connection to Ollama
    - List installed models
    - Run a chat completion example using the first available model