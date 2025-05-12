# Email-Insight-Engine
A beginner-friendly end-to-end NLP pipeline that extracts insights from unstructured customer support emails using Large Language Models (LLMs). This project performs:

 Email intent classification

 Sentiment analysis

 Summarization of email content

 Semantic similarity search (FAISS)

 Recommended next steps

All built using Hugging Face Transformers, Sentence Transformers, and FAISS, and runnable in Google Colab with no training required!

Features
LLM-based Classification: Uses a pre-trained transformer model to identify the email's intent (e.g., complaint, refund request, login issue).

Sentiment Analysis: Determines emotional tone (positive, negative, neutral).

Summarization: Generates a concise summary using a Hugging Face summarization pipeline.

Semantic Search: Uses sentence-transformers with FAISS to find contextually similar emails from past data.

Next Step Recommendation: Applies simple business logic to suggest a resolution based on email tone and intent.

Technologies Used
Python

Hugging Face Transformers

Sentence Transformers (paraphrase-MiniLM-L6-v2)

FAISS (Facebook AI Similarity Search)

Pandas

Google Colab
