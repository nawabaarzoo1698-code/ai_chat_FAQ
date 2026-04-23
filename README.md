# 🤖 AI FAQ Chatbot

An AI-powered FAQ chatbot built using Node.js and OpenAI API. This project demonstrates how to integrate Large Language Models (LLMs) into a backend system with clean architecture and scalable design.

---

## 🚀 Features

* AI-powered responses using OpenAI
* Clean modular architecture (Controller-Service pattern)
* Prompt engineering for better responses
* Error handling middleware
* Scalable backend structure
* Ready for RAG (Retrieval-Augmented Generation)

---

## 🏗️ Tech Stack

* Node.js
* Express.js
* OpenAI API

---

## 📂 Project Structure

```
src/
 ├── controllers/
 ├── services/
 ├── routes/
 ├── middlewares/
 ├── utils/
 └── config/
```

---

## ⚙️ Setup Instructions

1. Clone the repo:

```
git clone https://github.com/your-username/ai-faq-chatbot.git
```

2. Install dependencies:

```
npm install
```

3. Create `.env` file:

```
OPENAI_API_KEY=your_api_key
```

4. Run the server:

```
npm start
```

---

## 🧪 API Usage

### POST /api/chat

Request:

```
{
  "question": "What is microservices?"
}
```

Response:

```
{
  "answer": "Microservices is an architecture..."
}
```

---

## 🔥 Future Improvements

* Add vector database (RAG)
* Store chat history (MongoDB)
* Add authentication & rate limiting
* Streaming responses

---

## 💡 Learnings

* LLM API integration
* Backend architecture design
* Prompt engineering basics
* Building scalable AI services
