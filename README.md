
# Local LLM Chatbot

## Overview

This repository contains a Local LLM (Large Language Model) chatbot, running in a **Jupyter Notebook** environment, and utilizing the **Ollama** framework. This chatbot provides a local, private solution for experimenting with conversational AI, bypassing the need for cloud-based LLMs.

## Features

- **Microsoft Phi3:14B model**: Leverages the power of this 14-billion-parameter model for generating coherent and contextually accurate responses.
- **OpenAI-like Syntax**: The code syntax closely follows OpenAI’s API style, making it intuitive for developers familiar with OpenAI’s API to work with and modify.
- **Versatile Model Compatibility**: Designed for compatibility with multiple offline LLMs, including **llama3.1:8b** (Meta), **phi3:14b** (Microsoft), **gemma2:9b** (Google), and more. Switching between models is as simple as changing a single line of code to specify the model name.
- **Jupyter Notebook integration**: Easily explore, test, and modify code within an interactive notebook environment.
- **Ollama Framework**: Simplifies the implementation, allowing for rapid setup and deployment of the chatbot.

## Requirements

- **Jupyter Notebook**
- **Python 3.x**
- **Ollama Framework**

## Getting Started

1. **Clone this repository:**
   ```bash
   git clone https://github.com/parsafarshadfar/local_llm_chatbot.git
   ```
2. **install the Ollama framework**
   https://ollama.com/download
3. **Open and Run the Chatbot Notebook**:
   
    Open `LLM_chatbot.ipynb` in Jupyter Notebook and execute the cells to initialize and interact with the chatbot.

## Usage

This chatbot can be used as a conversational agent within Jupyter, suitable for experimenting with LLM-based dialogue, language tasks, and more. For switching to a different model, locate the line in the code where the model is initialized, and replace the model name with your preferred model name (e.g., `model = "llama3.1"`). This flexibility enables the chatbot to work with multiple LLMs by modifying only a single line of code.

## Contributing

Feel free to submit pull requests or open issues if you’d like to improve or troubleshoot this project. Contributions are welcome!

