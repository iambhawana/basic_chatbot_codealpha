# basic_chatbot_codealpha
A simple rule-based chatbot built using Python that responds to user inputs and demonstrates basic programming concepts such as loops, conditional statements, and string handling.
# 🤖 Basic ChatBot Using Python

## 📌 Project Overview
This is a simple rule-based chatbot developed using Python. The chatbot interacts with users by responding to predefined questions and continues the conversation until the user exits.

## 🚀 Features
- Greets the user
- Responds to common questions
- Handles user input
- Runs continuously until the user types "bye"
- Beginner-friendly Python project

## 🛠️ Technologies Used
- Python 3

## 📂 Project Structure
Basic-ChatBot/
│
├── chatbot.py
└── README.md

## 💻 Code

```python
print("===== BASIC CHATBOT =====")

while True:
    user_input = input("You: ").lower().strip()

    if user_input in ["hi", "hello", "hey"]:
        print("Bot: Hello! How can I help you today?")

    elif user_input == "how are you":
        print("Bot: I am doing well, thank you for asking!")

    elif user_input == "what is your name":
        print("Bot: My name is Python ChatBot.")

    elif user_input == "who created you":
        print("Bot: I was created using Python programming.")

    elif user_input == "bye":
        print("Bot: Goodbye! Have a great day.")
        break

    else:
        print("Bot: Sorry, I don't understand that. Please try another question.")
