# RAG System

I have built a Retrieval-Augmented Generation (RAG) system that can answer questions based on a set of documents. The system uses a combination of a vector database for document retrieval and a language model for generating answers.

You can put your documents in the `data/pdf_folder` folder, and the system will index them for retrieval. When you ask a question, the system retrieves relevant documents and generates an answer based on the content of those documents.

The right chunks would be picked based on the similarity of the question to the content of the documents. The system is designed to provide accurate and contextually relevant answers. 

For LLM it uses `llama-3.1-8b-instant` model. The vector database used is `chromadb`.