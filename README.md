# PDF Q&A System (GenAI Project)

A simple question-answering system over PDFs using HuggingFace Transformers + Sentence Transformers.

## The pipeline includes:
- Extracting text from PDFs using PyMuPDF (fitz)
- Embedding chunks with SentenceTransformers
- Finding the most relevant text chunk for a query
- Running Question-Answering with Hugging Face’s deepset/roberta-base-squad2
