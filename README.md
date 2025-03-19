# 🚀 **Chainlit Chatbot**  

This is a simple chatbot built using **Chainlit** 🛠️, a Python framework for creating conversational AI applications 🤖. The bot echoes back whatever the user says.  

## 📥 **Installation**  

Make sure you have **Python 3.8+** installed. Then, install Chainlit:  

```bash
pip install chainlit
```

## ▶️ **Usage**  

1. **Clone this repository** ⬇️:  
   ```bash
   git clone <https://github.com/ersa-rani/SIMPLE-CHATBOT>
   cd <SIMPLE-CHATBOT>
   ```
2. **Run the chatbot** 🏃‍♂️:  
   ```bash
   chainlit run main.py
   ```
3. **Open the provided URL** 🌍 in your browser to interact with the bot.  

## 📝 **Code Explanation**  

- **`import chainlit as cl`** → Imports the Chainlit library 🛠️.  
- **`@cl.on_message`** → Triggers the function when a user sends a message 💬.  
- **`async def main(message: cl.Message):`** → Asynchronous function to handle user messages ⚡.  
- **`response = f"You said: {message.content}"`** → Generates a response by echoing the user's message 🔄.  
- **`await cl.Message(content=response).send()`** → Sends the response back to the user 📤.  


![chatbot](https://github.com/user-attachments/assets/fb843d25-fb5a-44a8-8c32-ffa04afe05a6)
