# CloudDesk CRM Support Chatbot

An Enterprise **Retrieval-Augmented Generation (RAG)** AI Support Chatbot built using **Dify**, **Ollama**, and **Llama 3.2**. The chatbot answers customer support questions using only CloudDesk CRM documentation, providing grounded responses with citations while preventing hallucinations.

---

# Problem Statement

Customer support teams spend significant time answering repetitive questions related to product features, pricing, refunds, security, troubleshooting, and account management.

This project demonstrates how a RAG-based chatbot can retrieve information from enterprise documentation and generate accurate, context-aware responses.

---

# Features

-  Retrieval-Augmented Generation (RAG)
-  Knowledge Base Search
-  Local LLM using Ollama
-  Built using Dify Workflow
-  Citation-based Responses
-  Hallucination Prevention
-  Out-of-Scope Question Handling

---

#  Tech Stack

| Technology | Purpose |
|------------|---------|
| Dify | AI Workflow Builder |
| Ollama | Local LLM Runtime |
| Llama 3.2 | Large Language Model |
| Knowledge Base | Enterprise Documentation |
| Docker | Local Deployment |

---

#  Workflow

```
User Question
      │
      ▼
Knowledge Retrieval
      │
      ▼
Llama 3.2 (Ollama)
      │
      ▼
Grounded Answer + Citations
```

---

#  Project Screenshots

### Workflow

![Workflow](Chatbot%20Workflow.png)

---

### Knowledge Base

![Knowledge Base](Chatbot%20Knowledge%20Base.png)

---

### Refund Policy Response

![Refund](Chatbot%20Refund%20Policy.png)

---

### Password Reset

![Password Reset](Chatbot%20Password%20Resect.png)

---

### Out-of-Scope Question

![Out of Scope](Chatbot%20Out-of-Scope%20Question.png)

---

#  Example Questions

- What is the refund policy?
- How do I reset my password?
- What are the subscription plans?
- What are the SLA response times?
- Who is the CEO of Microsoft?

---

#  Learning Outcomes

- Built an Enterprise RAG Chatbot
- Worked with Dify AI Workflows
- Used Ollama to run a Local LLM
- Implemented Retrieval-Augmented Generation
- Improved response reliability using Knowledge Retrieval
- Prevented hallucinations through grounded responses

---

#  Future Improvements

- Voice-based support
- Multi-language support
- Integration with CRM systems
- Live chat support
- Analytics Dashboard

---

#  Author

**Mandara Manasa**

MBA – Technology Management  
Aspiring Product Manager | AI & Product Enthusiast
