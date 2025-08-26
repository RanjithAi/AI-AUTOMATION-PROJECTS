# 🚀 AI-Powered Customer Support Workflow (n8n + AI)

This project is an AI-powered **customer support automation workflow** built with n8n, designed to handle support emails faster, smarter, and more consistently.

---

## 🔹 Features
- 📩 **Gmail Trigger (via GCP)** → Capture incoming support emails  
- 🧾 **Text Classifier (OpenAI)** → Identify support requests vs. other emails  
- 🤖 **AI Agent (OpenAI Chat Model)** → Generate intelligent responses  
- 📚 **Pinecone + OpenAI Embeddings** → Retrieve policy & FAQ knowledge  
- ✅ **Automation** → Label and reply to emails instantly  

---

## 🔹 Workflow Overview

### 1️⃣ Full n8n Workflow

<img width="1231" height="573" alt="WORKFLOW" src="https://github.com/user-attachments/assets/83316511-01b8-4cbf-a98c-aee616eaf33a" />

### 2️⃣ Text Classifier Node (OpenAI)

<img width="1364" height="686" alt="TEXT_CLASSIFIER" src="https://github.com/user-attachments/assets/f4e41da6-9bdf-4931-bb06-ea4438e840f7" />

### 3️⃣ AI Agent Node (OpenAI Chat Model)

<img width="1351" height="692" alt="AI_AGENT" src="https://github.com/user-attachments/assets/57f09c8a-bf6c-4861-ac1b-7145faade7c6" />

### 4️⃣ Pinecone Vector Database Setup

<img width="1343" height="686" alt="PINECONE" src="https://github.com/user-attachments/assets/40c860a5-4877-4191-b836-c00a2d767b3d" />

### 5️⃣ Gmail Trigger & Received Mail

<img width="774" height="546" alt="RECIEVED_MAIL" src="https://github.com/user-attachments/assets/453e482b-21bc-4e42-9729-709a3e8d6113" />

---
## 🎥 Demo Video  

https://github.com/user-attachments/assets/b72057e9-ed8a-4091-969b-1ec47e163e8a

---
## 🔹 Tech Stack
- **n8n (workflow automation)**  
- **OpenAI (LLMs + embeddings)**  
- **Pinecone (vector database)**  
- **Google Cloud Platform (Gmail API)**  

---

## 🔹 Use Cases
- Automating **customer support email replies**  
- Scaling support teams without extra manpower  
- Providing **consistent, policy-driven answers**  
- Example project for learning **AI + Automation workflows**  

---

## 🔹 How to Use
1. **Clone this repo**  
2. **Import workflow JSON** into n8n  
3. **Set up API keys** for OpenAI, Pinecone, and GCP  
4. **Upload your FAQs/policies** into Pinecone  
5. **Run workflow** → Watch emails get answered automatically 🚀  

---

## 💡 Future Improvements
- Sentiment analysis to **prioritize urgent tickets**  
- Multi-language support 🌍  
- Escalation to **human agents** when confidence is low  
- Integration with **Slack/Teams for live updates**  

---

⭐ If this project helps you, don’t forget to **star this repo** and share your feedback!  
