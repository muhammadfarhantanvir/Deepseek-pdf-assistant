# AI pdf Assistant 📘

An intelligent document analysis assistant powered by DeepSeek LLM and LangChain. Process PDF documents and get AI-powered insights through natural language queries.

## Key Features

- 📄 PDF Document Processing with text extraction
- 🧠 DeepSeek LLM integration for intelligent Q&A
- 🔍 Semantic search using vector embeddings
- 💬 Interactive chat interface with context-aware responses
- 🎨 Custom UI theme with enhanced visual styling

## Requirements

- Python 3.8+
- Ollama installed and running locally
- DeepSeek-r1 model available in Ollama

## Installation

```bash
# Clone repository
git clone https://github.com/muhammadfarhantanvir/Deepseek-pdf-assistant.git
cd Deepseek-pdf-assistant

# Install dependencies
pip install -r requirements.txt

# Download DeepSeek model (run in separate terminal)
ollama pull deepseek-r1:1.5b

# Launch application
streamlit pdf_assistant.py