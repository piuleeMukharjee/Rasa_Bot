## 💬 AI Chatbot with Rasa
# 📌 Overview

This project uses Rasa, an open-source Python framework for building custom AI chatbots powered by Natural Language Understanding (NLU) and Natural Language Processing (NLP).
With Rasa, you can:

Understand user input in natural language.

Create conversational flows.

Trigger custom actions.

Train and deploy your chatbot locally or in production.

# 🧰 Tech Stack

Python 3.9+

Rasa (NLU + Core for dialogue management)

Custom Actions (Python scripts)

(Optional) Rasa X for conversation visualization and testing

# ⚙️ Installation

Run in terminal or Jupyter Notebook:

# Install Rasa
~~~
pip install rasa
~~~


# Verify installation:
~~~
rasa --version
~~~

# 🗂️ Project Structure
~~~
my-chatbot/
|── actions/                 # Custom action scripts
│   └── actions.py
├── data/                    # NLU and conversation training data
│   ├── nlu.yml
│   ├── stories.yml
│   └── rules.yml
├── domain.yml               # Intents, entities, slots, templates
├── config.yml               # Pipeline and policies
├── credentials.yml          # Channels configuration
├── endpoints.yml            # Action server endpoints
└── README.md
~~~
# ▶️ How to Run
1) Initialize Rasa project
~~~
rasa init
~~~
2) Train the model
~~~
rasa train
~~~
3) Run the chatbot
~~~
#In one terminal:

rasa run actions


#In another terminal:

rasa shell
~~~

# 📌 Example Conversation
You: hello
Bot: Hey! How can I help you today?

You: tell me a joke
Bot: Why don’t skeletons fight each other? They don’t have the guts.

# 🎯 Learning Outcomes

Understand NLU pipelines and tokenization.

Build domain-driven conversation flows.

Implement custom Python actions.

Train and evaluate an AI conversational model.
