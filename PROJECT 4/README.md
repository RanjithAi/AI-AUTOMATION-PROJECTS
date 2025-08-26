# 🚀 AI-Powered Customer Support Workflow (n8n + AI)

This project is an AI-powered **customer support automation workflow** built with n8n, designed to handle support emails faster, smarter, and more consistently.

---

## 🔹 Features
📩 **Gmail Trigger (via GCP)** → Capture incoming support emails  
🧾 **Text Classifier (OpenAI)** → Identify support requests vs. other emails  
🤖 **AI Agent (OpenAI Chat Model)** → Generate intelligent responses  
📚 **Pinecone + OpenAI Embeddings** → Retrieve policy & FAQ knowledge  
✅ **Automation** → Label and reply to emails instantly  

---

## 🔹 Workflow Overview
1. **Trigger (Gmail)** – Fetch incoming customer emails  
2. **Text Classifier (OpenAI)** – Categorize email type  
3. **AI Agent (OpenAI)** – Draft smart, contextual replies  
4. **Pinecone Search** – Retrieve FAQ/policy info with embeddings  
5. **Reply via Gmail** – Send automated customer response  

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
