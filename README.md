# 🤖 PCOS Chatbot using Dialogflow

This repository contains a **Dialogflow-based chatbot** developed for **Lyra**, a web application that focuses on **PCOS (Polycystic Ovary Syndrome) risk prediction** and awareness.

---

## 🧠 About the Chatbot

This chatbot was built using [Dialogflow ES](https://dialogflow.cloud.google.com/) and is designed to provide friendly and helpful responses to users interacting with the Lyra app. It acts as a conversational assistant to:
- Explain what PCOS is
- Answer common questions about symptoms, diagnosis, and treatments
- Provide general support, tips, and lifestyle advice for those at risk

---

## 💡 Features

- ✅ Predefined **intents** for over 30+ PCOS-related questions
- ✅ Multiple **training phrases** per intent to ensure natural interaction
- ✅ Supportive and empathetic tone designed for user comfort
- ✅ Integrated into a **Bootstrap + Flask web app**
- ✅ Custom avatar and support using Dialogflow Messenger

---

## 🚀 How It Works

1. Users click on the floating chat icon in the Lyra app.
2. Dialogflow Messenger launches an embedded chat window.
3. The chatbot listens for user queries and matches them with the closest intent.
4. It responds with carefully crafted, friendly answers about PCOS and related health topics.

---

## 🌐 Deployment

The chatbot is embedded in the Lyra app using:

```html
<script src="https://www.gstatic.com/dialogflow-console/fast/messenger/bootstrap.js?v=1"></script>

<df-messenger>
  intent="WELCOME"
  chat-title="Lyra"
  agent-id="YOUR-AGENT-ID" #create a new agent on DialogFlow with the given intent files and add the agent ID here.
  language-code="en"
  chat-icon="https://yourdomain.com/static/images/pcos_avatar.png"
  chat-background-color="#fff8f2"
  chat-bubble-color="#ffe2e6"
  user-chat-bubble-color="#e6f3f0"
  accent-color="#d06e91"
</df-messenger>
```
