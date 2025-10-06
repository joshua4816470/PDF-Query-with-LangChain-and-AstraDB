# PDF-Query-with-LangChain-and-AstraDB


This repository showcases a complete Retrieval-Augmented Generation (RAG) pipeline that allows users to query any PDF and get instant, context-based answers powered by LangChain, OpenAI, and AstraDB.

🔍 Key Features

Extracts text from PDFs using PyPDF2

Splits long text into semantic chunks via LangChain’s CharacterTextSplitter

Converts chunks into vector embeddings using OpenAIEmbeddings

Stores and retrieves vectors from Cassandra AstraDB for high-speed similarity search

Generates intelligent, context-driven answers using OpenAI’s LLM

Supports real-time Q&A from command line

🧠 Tech Stack

LangChain – Orchestrates LLMs, embeddings, and retrieval

OpenAI API – For embeddings and generative responses

Cassandra AstraDB – Cloud-native vector database

PyPDF2 – For PDF text extraction

Python 3.10+

⚙️ Project Workflow

Extract text from PDF

Split into overlapping chunks

Embed using OpenAI

Store vectors in AstraDB

Retrieve and answer queries via LangChain

💡 Use Case Example

You can query research papers, manuals, or academic PDFs — for example, comparing Neuro-Symbolic AI and Statistical Relational AI papers to derive conceptual similarities through embeddings.

📊 Key Metrics

~50 text chunks processed from a 20-page PDF

<2-second retrieval latency

~90% semantic relevance accuracy
