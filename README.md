PDF-Powered AI Chatbot
-----------------------


Technologies: Node.js, LangChain, Google Gemini, Pinecone, dotenv

Description:
Developed an AI-driven conversational system that allows users to query PDF documents in natural language. The system leverages document embeddings, semantic search, and generative AI to provide accurate, context-aware answers directly from the uploaded content.

Key Features:
-----------


PDF Ingestion & Chunking: Loads PDFs and splits them into manageable text chunks for precise embedding.

Vector Embeddings: Uses Google Gemini (text-embedding-004) to convert text chunks into high-dimensional vectors.

Semantic Search: Stores embeddings in Pinecone for fast and accurate retrieval of relevant document sections.

Context-Aware Q&A: Rewrites user queries into standalone questions and generates answers using Gemini (gemini-2.0-flash) strictly based on the document content.

Conversational Memory: Maintains chat history to handle follow-up questions intelligently.

Interactive CLI Interface: Provides a user-friendly terminal-based chat interface for continuous Q&A sessions.

Impact:
-------


Enables students and professionals to interactively learn from PDFs without manually searching through the document.

Ensures answers are reliable, concise, and strictly document-based, preventing misinformation.

Demonstrates proficiency in AI embeddings, vector databases, and LLM integrations for real-world knowledge retrieval applications.
