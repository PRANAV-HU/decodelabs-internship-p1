🤖 Rule-Based AI Chatbot with Gemini API

A hybrid AI chatbot developed using Python and the Google Gemini API as part of the DecodeLabs Artificial Intelligence Internship - Project 1.

The chatbot combines rule-based intent recognition with Generative AI. It first checks whether the user's query matches predefined intents. If no intent is found, it forwards the request to the Gemini model, providing intelligent responses while maintaining fast execution for common interactions.

🚀 Features
Handles 5+ predefined intents
Greeting
Goodbye
Help
About
Thank You
Uses a continuous chat loop
Sanitizes user input using lower() and strip()
Falls back to the Gemini API for unknown queries
Gracefully handles API errors
Easy to extend with additional intents
Simple and beginner-friendly Python implementation
🛠 Technologies Used
Python 3.x
Google Gemini API
google-genai SDK
📂 Project Structure
Rule-Based-AI-Chatbot/
│
├── chatbot.py
├── README.md
└── requirements.txt
⚙️ Installation

Clone the repository

git clone https://github.com/yourusername/Rule-Based-AI-Chatbot.git

Move into the project folder

cd Rule-Based-AI-Chatbot

Install dependencies

pip install -U google-genai
🔑 Configure API Key

Replace

client = genai.Client(api_key="YOUR_API_KEY")

with your own Gemini API key.

▶️ Running the Project
python chatbot.py

Example

You: Hello
Chatbot: Hello! How can I help you today?

You: Who are you?
Chatbot: I'm an AI chatbot powered by Google's Gemini API.

You: Tell me about Artificial Intelligence.
Chatbot: Artificial Intelligence (AI) is...
🧠 Chatbot Workflow
User Input
     │
     ▼
Input Sanitization
(lower() + strip())
     │
     ▼
Intent Matching
     │
 ┌───┴──────────┐
 │              │
Intent Found   No Intent
 │              │
 ▼              ▼
Rule Response  Gemini API
      │
      ▼
 Display Response
📋 Implemented Intents
Intent	Example Inputs
Greeting	Hi, Hello, Hey
Goodbye	Bye, Exit, Quit
Help	Help, Commands
About	Who are you?
Thanks	Thank you, Thanks
🎯 Learning Outcomes

This project demonstrates:

Rule-based decision making
Intent recognition
Python dictionaries
Functions
Exception handling
Control flow
Infinite loops
API integration
Hybrid AI chatbot architecture
🔮 Future Improvements
Add more predefined intents
NLP-based intent classification
Voice input and speech output
GUI using Tkinter or Streamlit
Conversation history
Multi-language support
Context-aware responses
Sentiment analysis
Database for storing chat history
📸 Sample Conversation
You: Hello
Chatbot: Hello! How can I help you today?

You: Thanks
Chatbot: You're welcome!

You: What is Machine Learning?
Chatbot: Machine Learning is a branch of Artificial Intelligence...

You: Bye
Chatbot: Goodbye! Have a great day!
📖 Key Concepts Used
Rule-Based AI
Intent Recognition
Hybrid AI Systems
Conditional Statements
Dictionaries
Functions
Exception Handling
API Calls
Continuous Chat Loop
Input Sanitization
📌 Project Objective

The objective of this project is to build a hybrid chatbot that combines deterministic, rule-based responses for common user intents with the flexibility of a Large Language Model (Gemini API) for answering open-ended questions. This approach improves response speed for known commands while leveraging generative AI for broader conversational capabilities.

## Author

**Pranav V B**

Decode Labs Internship – Project 1

---

## Acknowledgements

- Decode Labs
- Google Gemini API
- Python Community

