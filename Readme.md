# RAG Chatbot with LangChain & GPT

An intelligent chatbot leveraging Retrieval-Augmented Generation (RAG) using LangChain framework and OpenAI's GPT models.

## 🛠️ Technologies

- **LLM Framework**: LangChain
- **Language Model**: OpenAI GPT-3.5/GPT-4
- **Language**: Python 3.x
- **Vector Store**: FAISS / ChromaDB
- **Embeddings**: OpenAI Embeddings

## 📋 Features

- Retrieval-Augmented Generation (RAG) architecture
- Context-aware responses using document retrieval
- Integration with OpenAI API
- Conversational memory management

## 🚀 Installation
```bash
# Clone the repository
git clone https://github.com/MohdSarar/ChatBot-gpt---Langchain.git
cd ChatBot-gpt---Langchain

# Install dependencies
pip install langchain openai faiss-cpu python-dotenv

# Set up environment variables
echo "OPENAI_API_KEY=your_api_key_here" > .env
```

## ⚙️ Configuration

Create a `.env` file with your OpenAI API key:

OPENAI_API_KEY=sk-your-api-key-here 

## 🏗️ Architecture
User Query → Embedding → Vector Search → Context Retrieval → LLM → Response

## 👤 Author

**Mohammed ABUSARAR** - [GitHub](https://github.com/MohdSarar)