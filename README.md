# RAG-Chatbot

A simple **Retrieval-Augmented Generation (RAG)** chatbot built in Python.  
It retrieves relevant context from a knowledge base and uses it to answer user queries more accurately.

---

## Overview

This project implements a conversational chatbot powered by RAG:  
- It stores documents (or knowledge) in an embedding-indexed vector store.  
- Given a user query, it retrieves the most relevant context.  
- It then uses that context + the query to generate an answer using a language model.

This approach helps reduce hallucinations by grounding answers in actual source content.

---

## Features

- Context-aware responses from a knowledge corpus  
- Retrieval + generation hybrid architecture  
- Easy to extend with new data  
- Minimal dependencies  
- Suitable for prototyping and experimenting with RAG setups  

---

## Prerequisites

- Python 3.10 or newer  
- (Optional) GPU for faster model inference (depending on the model used)  
- pip (or any package manager)  
- Internet connection (if using remote LLM / embedding services)  

---

## Installation

1. Clone this repository:

    ```bash
    git clone https://github.com/jayanibv/RAG-chatbot.git
    cd RAG-chatbot
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Set up environment variables.

---

## Usage

Run the main application:

```bash
python main.py
