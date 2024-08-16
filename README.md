# Document-Chatbot

 DocumentGPT is a Streamlit application designed to allow users to interact with the content of their uploaded documents (PDF and DOCX files) using an AI chatbot. This app leverages the power of OpenAI's GPT-3.5-turbo model and the langchain library to provide intelligent, conversational responses based on the contents of the documents.

Key Features:

File Upload: Users can upload multiple files (PDF and DOCX formats). The app reads and extracts text from these files.

Text Processing: The extracted text is split into manageable chunks for efficient processing and retrieval.

Vector Store Creation: A vector store is created using the Hugging Face embedding model (all-MiniLM-L6-v2) and FAISS for efficient semantic search within the document contents.

Conversational Chain: The app creates a conversational chain that allows users to ask questions about their documents. The chatbot provides responses based on the extracted and processed text.

Memory Buffer: The app keeps track of the chat history to maintain context during the conversation.

OpenAI Integration: The app uses OpenAI's GPT-3.5-turbo model to generate responses. The API key can be set within the app.
