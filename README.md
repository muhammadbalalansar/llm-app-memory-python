# 🧠 LLM App with Memory

**By Muhammad Balal Ansar (Cyber Security Expert)**

This Streamlit app is an AI-powered chatbot that uses OpenAI's GPT-4o model with a persistent memory feature. It allows users to have conversations with the AI while maintaining context across multiple interactions.

---

### ✨ Features

* Utilizes OpenAI's GPT-4o model for generating responses
* Implements persistent memory using Mem0 and Qdrant vector store
* Allows users to view their conversation history
*  Provides a user-friendly interface with Streamlit

--

### 🚀 How to Get Started

1. **Clone the GitHub repository**
   ```bash
   git clone https://github.com/muhammadbalalansar/llm-app-memory-python.git
   cd llm-app-memory-python
Install the required dependencies

Bash
pip install -r requirements.txt
Ensure Qdrant is running
The app expects Qdrant to be running on localhost:6333. Adjust the configuration in the code if your setup is different.  

Bash
docker pull qdrant/qdrant

docker run -p 6333:6333 -p 6334:6334 \
    -v $(pwd)/qdrant_storage:/qdrant/storage:z \
    qdrant/qdrant
Run the Streamlit App

Bash
streamlit run llm_app_memory.py
