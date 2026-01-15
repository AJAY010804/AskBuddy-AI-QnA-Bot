# ✨ AskBuddy – AI QnA ChatBot 🚀

AskBuddy is an AI-powered Question & Answer chatbot built using **Streamlit**, **LangChain**, and **Groq LLM**.  
It provides fast, interactive responses using the **LLaMA 3.1 model** and maintains chat history for a smooth user experience.

---

## 🔥 Features

- 🤖 AI-powered QnA chatbot
- ⚡ Responses using Groq LLM
- 🧠 Chat memory using Streamlit session state
- 💬 Clean chat-style UI

---

## 🛠️ Tech Stack

- **Python**
- **Streamlit**
- **LangChain**
- **Groq AI (LLaMA 3.1 – 8B)**
- **python-dotenv**

---

## 📂 Project Structure

```
AskBuddy-AI-QnA-Bot/
│
├── app.py            # Main Streamlit app & UI logic
├── requirements.txt  # Project dependencies
└── README.md         # Project documentation
```
---

## 🚀 Getting Started

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/AskBuddy-AI-QnA-Bot.git
cd AskBuddy-AI-QnA-Bot
```
### 2️⃣ Create Virtual Environment (Recommended)
```bash
python -m venv venv
```
Activate it:
#### Windows
```bash
venv\Scripts\activate
```
#### Mac/Linux
```bash
source venv/bin/activate
```
### 3️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```
### 4️⃣ Setup Environment Variables
Create a .env file in the root directory:
```bash
GROQ_API_KEY=your_groq_api_key_here
```
👉 Get your API key from: https://console.groq.com
### 5️⃣ Run the Application
```bash
streamlit run app.py
```

### 💡 How It Works
-  User enters a question in the chat input
-  Query is sent to Groq LLM via LangChain
-  AI response is displayed instantly
-  Chat history is stored using Streamlit session state

---
<p align="center"><b>B.Tech CSE | AI & Data Science Enthusiast</b></p>

