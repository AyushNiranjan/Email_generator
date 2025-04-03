# 📧 AI-Powered Email Assistant

This project is an **AI-powered email assistant** that automatically reads unread emails from Gmail, generates professional replies using **Groq's Llama 3 model**, and sends responses back to the sender.

---
## 🚀 Features
-  Fetches the **latest unread email** from Gmail.
-  Generates a **context-aware reply** using **Groq's Llama 3 model**.
-  Sends the AI-generated reply using **SMTP (Simple Mail Transfer Protocol)**.
-  Secure authentication with **IMAP & SMTP**.
### ** Enable IMAP and Generate App Password**
To allow the script to access your Gmail account, follow these steps:
- Enable **IMAP** in your Gmail settings.
- Generate an **App Password** from [Google Security Settings](https://myaccount.google.com/apppasswords).
- ## 📌 How It Works
### **🔹 Step 1: Fetch Unread Email**
- Connects to Gmail using **IMAP**.
- Searches for **unread emails**.
- Retrieves the **last unread email** (sender, subject, body).

### **🔹 Step 2: AI-Generated Reply**
- Uses **Groq's Llama 3 model** to generate a professional reply.

### **🔹 Step 3: Send Reply via SMTP**
- Uses **SMTP** to send the reply back to the sender.
