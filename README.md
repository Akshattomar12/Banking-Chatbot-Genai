# Banking-Chatbot-Genai
his project is a RAG-based (Retrieval-Augmented Generation) banking chatbot built with Botpress and Pathway
Features

✔️ Expense Tracking – Automatically logs and categorizes expenses.
✔️ Smart Savings Suggestions – Provides AI-driven savings recommendations.
✔️ Real-time Queries – Answers user queries related to finances.
✔️ Pathway Integration – Uses Pathway for real-time data streaming and LLM-based responses.
✔️ Secure & Scalable – Built using robust AI and NLP models.

Tech Stack

Botpress (Conversational AI)

Pathway (Real-time data processing)

Python (Backend processing)

LLM (Large Language Model) for smart responses


Demo Video

Watch the working demo here:
https://drive.google.com/file/d/1ubGMnDB4WajOsRiM3zxK4_03AhxeA6hB/view?usp=sharing

A detaoled description Explaining its purpose and integration with LLMs

This project is a Banking Chatbot that uses Large Language Models (LLMs) and Pathway to provide users with intelligent financial assistance. It is designed to help users track their expenses, receive savings suggestions, and ask real-time banking queries through a conversational interface.

The chatbot is built using Botpress for the dialogue system and Pathway for integrating real-time data pipelines and enabling Retrieval-Augmented Generation (RAG). It pulls relevant financial data and context using RAG and responds through an LLM, offering highly accurate and contextual replies to user queries.

Purpose

To simplify personal finance management using AI.

To allow users to interact naturally through chat and get instant, personalized financial insights.

To demonstrate a real-world use case of GenAI in the financial domain.


Integration with LLMs

Pathway handles real-time streaming of user queries and context.

The chatbot uses a RAG pipeline to retrieve relevant data from documents or transaction logs.

The LLM (hosted via Botpress or integrated API) generates natural language responses based on the retrieved data.

This combination ensures responses are accurate, contextual, and personalized





Setup Instructions

1. Clone the Repository

git clone https://github.com/Akshattomar12/Banking-Chatbot-GenAI.git
cd Banking-Chatbot-GenAI

2. Install Dependencies

Ensure you have Python 3.8+ installed. Then run:

pip install -r requirements.txt

3. Configure API Keys

Create a .env file in the root directory and add your Thinkstack AI and Pathway credentials:

THINKSTACK_API_KEY=https://app.thinkstack.ai/bot/index.html?chatbot_id=67e98733c8593856f0f7a01c


4. Run the Application

python main.py

5. Access the Chatbot

Open your Botpress or web client as configured.

Start chatting with your banking assistant.



---

Usage Instructions

1. Open the chat interface 


2. Ask financial questions such as:

"How much did I spend last week?"

"Give me a savings plan."

"Track my monthly expenses."



3. The chatbot uses Pathway to retrieve relevant context and Thinkstack AI to generate smart replies.


4. The conversation updates in real time and adapts to user input dynamically.



