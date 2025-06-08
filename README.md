# TinyLlama and Mistral 
Anime Q&amp;A System with Haystack &amp; TinyLlama ;Mistral

This project implements an anime question-answering system using Haystack, TinyLlama (served locally via Ollama), and Gradio. The system allows users to ask questions about a dataset of anime information, and it generates contextually relevant, natural language answers.

Key Features:
Retrieval-based Model: Uses BM25Retriever to efficiently search through a large anime dataset stored in InMemoryDocumentStore.

Generative Model: TinyLlama, a lightweight language model, generates answers based on the retrieved context, providing detailed and coherent responses.

Interactive Interface: A simple and user-friendly Gradio interface enables users to interact with the system and ask questions about various anime series.

Local Deployment: The TinyLlama model is served locally using Ollama, reducing dependency on external APIs and providing fast response times.


