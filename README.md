# Legal Chatbot with Document Processing

This project implements a legal chatbot that can answer questions based on uploaded PDF documents. It uses a fine-tuned TinyLlama model for natural language processing and FAISS for efficient document retrieval.

## Features

- PDF document processing and indexing
- Question-answering based on uploaded documents
- User-friendly interface using Gradio

## Technologies Used

- Python
- Transformers (Hugging Face)
- LangChain
- FAISS
- Gradio

## Setup and Installation

1. Clone this repository
2. Install the required packages:
pip install transformers langchain faiss-cpu gradio torch
3. Download the fine-tuned TinyLlama model and place it in the `legal_qa_tinyllama_model` directory

## Usage

1. Run the main script:
python main.py
2. Open the provided URL in your web browser
3. Upload PDF documents using the "Upload Document" tab
4. Ask legal questions in the "Chat" tab

## Note

This chatbot is for demonstration purposes only and should not be used as a substitute for professional legal advice.

## License

[MIT License](LICENSE)
