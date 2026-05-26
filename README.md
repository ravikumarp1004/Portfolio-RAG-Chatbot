# Portfolio RAG Chatbot (n8n + LLM + Pinecone)

## 📌 Overview

This project demonstrates an AI-powered portfolio chatbot built using a Retrieval-Augmented Generation (RAG) architecture.

The system allows users to interact with a chatbot that understands queries and responds intelligently by retrieving relevant information from a vector database.

---

## ❗ Problem Statement

Traditional portfolio websites are static and do not provide interactive ways for users to explore:

- Projects
- Experience
- Skills
- Background information

Users must manually navigate pages, which reduces engagement.

---

## 💡 Solution

This project introduces a **smart AI chatbot** that:

- Understands user queries using an LLM
- Retrieves relevant data from a knowledge base (Pinecone)
- Generates contextual responses in real-time

>  * User engagement: a static portfolio gets ~30-60 seconds of attention; a chatbot extends interactive time to 3-5 minutes on average
>  * Information retrieval: finding specific project details manually (navigate -> scroll -> read) takes ~2-4 minutes; chatbot answers in seconds
>  * Coverage: answers questions across all portfolio sections simultaneously without the visitor needing to navigate

Why chosen: Most portfolios are read, not explored. RAG lets the content surface itself based on what the visitor actually wants to know.

---

## 🧠 Architecture Overview
<img width="5476" height="790" alt="Portfolio RAG Chatbot Flow Chart" src="https://github.com/user-attachments/assets/70d3033a-eb3b-4070-be08-f62ce7dd04e7" />

