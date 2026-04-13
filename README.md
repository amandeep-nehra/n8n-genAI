Advanced RAG Orchestrator: Hybrid AI Workflows
This repository contains a comprehensive implementation of Retrieval-Augmented Generation (RAG) systems, ranging from low-code automation to custom neural pipelines. Developed as part of the Generative AI curriculum at RPTU Kaiserslautern-Landau, these projects demonstrate the ability to build robust, document-grounded AI agents.

📁 Repository Contents
/n8n-Workflows: Production-ready JSON exports for automated document ingestion and conversational retrieval.
/Python-Notebooks: Custom LangChain implementation of advanced retrieval strategies.
/Demos: Screen recordings demonstrating the system successfully answering complex queries from unstructured data.

🚀 Technical Highlights
1. n8n Orchestration (Low-Code/No-Code)
Workflow Logic: Designed a dual-flow system for PDF Ingestion and Conversational Retrieval.
Vector Integration: Utilized Supabase Vector Store and HuggingFace Inference (distilbert-base) to manage 768-dimensional document embeddings.
Agentic Reasoning: Implemented an AI Agent Node with Groq (Llama 3) to synthesize grounded answers from retrieved context.

2. Custom LangChain RAG (High-Code)
Semantic Chunking: Leveraged RecursiveCharacterTextSplitter to maintain context window efficiency.
Advanced Retrieval (RRR): Implemented Rewrite-Retrieve-Respond logic to optimize user queries before searching the vector database.
Self-Refinement: Integrated Self-RAG loops to iteratively evaluate and improve response accuracy, significantly reducing hallucinations.

🛠 Tech Stack
LLMs: Groq (Llama-3.1-70b), HuggingFace Inference.
Orchestration: n8n, LangChain, Docker.
Vector Databases: Supabase, ChromaDB.
Tools: Python, Jupyter, VS Code.

📈 Impact for Research Roles
This project serves as a "Proof of Work" for Intelligent Systems and Software Engineering student assistant roles. It proves competence in:
Systematic Evaluation: Testing different retrieval strategies for performance.
Reproducibility: Providing complete JSON workflows and documented code.
Modern AI Stack: Hands-on experience with the latest Agentic AI frameworks.
