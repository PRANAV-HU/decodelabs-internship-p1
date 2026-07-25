# COMMAND-LINE AI CHATBOT

## Overview

This project was developed as part of the **Decode Labs Internship Program**. It is a command-line AI chatbot built using Google's Gemini API. The chatbot accepts user input, sends it to the Gemini model, and displays AI-generated responses in real time.

---

## Features

- AI-powered conversational chatbot
- Uses Google's Gemini API
- Interactive command-line interface
- Continuous conversation support
- Exit command support (`quit`, `exit`, `bye`)
- Simple and beginner-friendly Python implementation

---

## Tech Stack

- Python 3
- Google Gemini API
- Google GenAI SDK

---

## Project Structure

```
DecodeLabs-P1/
│── gemini.py
│── myversion.py
└── README.md
```

---

## Installation

### 1. Clone the repository

```bash
git clone <repository-url>
cd DecodeLabs-P1
```

### 2. Install dependencies

```bash
pip install -U google-genai
```

---

## API Key Setup

Create an environment variable named:

```
GEMINI_API_KEY
```

Then access it in Python:

```python
import os
from google import genai

client = genai.Client(api_key=os.getenv("GEMINI_API_KEY"))
```

> **Note:** Never upload your API key to GitHub.

---

## Running the Project

```bash
python myversion.py
```

or

```bash
python gemini.py
```

---

## Example

```
You: Hello

Chatbot:
Hello! How can I help you today?

You: Explain Python lists.

Chatbot:
Python lists are ordered, mutable collections...
```

---

## Learning Outcomes

During this project, I learned:

- Working with REST-based AI APIs
- Using the Google GenAI SDK
- Python function design
- User input handling
- Building interactive command-line applications
- Git and GitHub version control

---

## Future Improvements

- Graphical User Interface (GUI)
- Chat history support
- Markdown response formatting
- Voice input/output
- Web-based interface using Flask or Streamlit

---

## Author

**Pranav V B**

Decode Labs Internship – Project 1

---

## Acknowledgements

- Decode Labs
- Google Gemini API
- Python Community

