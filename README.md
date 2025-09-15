# Project Setup

This document provides instructions for setting up the necessary dependencies to run this project.

## Python Dependencies

Install the required Python libraries using pip:

```bash
pip install joblib scikit-learn sentence-transformers hf-xet
```

Alternatively, you can add these dependencies to your `requirements.txt` file and install them all at once:

```bash
pip install -r requirements.txt
```

## Ollama Installation

For running the language models, you need to have Ollama installed.

### Linux & macOS

You can install Ollama by running the following command in your terminal:

```bash
curl -fsSL https://ollama.com/install.sh | sh
```

### Windows

Download and run the executable from the [Ollama website](https.ollama.com).
