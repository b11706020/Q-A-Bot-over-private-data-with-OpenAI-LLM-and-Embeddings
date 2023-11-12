# Q-A-Bot-over-private-data-with-OpenAI-LLM-and-Embeddings
Python-based Q&amp;A bot using OpenAI's LLM and LangChain's Vector Index Database for text extraction and processing. Features include PDF data extraction, tokenization, efficient data management, OpenAI embeddings for context analysis, and customizable query handling for diverse informational needs.
# Features
PDF Text Extraction: Extracts text from PDF files using PyMuPDF.
Data Cleaning: Implements text manipulation for data normalization.
Data Management: Uses pandas for organizing and processing data.
Tokenization and Chunking: Tokenizes text using tiktoken and manages token limits.
OpenAI Embeddings: Converts texts into embeddings for contextual analysis.
Question Answering: Answers queries based on context derived from data.
# Prerequisites
Python 3.x
PyMuPDF
Pandas
NumPy
OpenAI API key
TikToken
# Installation
Clone the repository: git clone 
Navigate to the project directory: cd [project directory]
Install dependencies: pip install -r requirements.txt
# Usage
Extract text from PDF: fitz.open('[path-to-pdf]')
Clean and process data: [data processing steps]
Generate embeddings: openai.Embedding.create(...)
Answer questions: answer_question(df, question="...")
# Contributing
Contributions, issues, and feature requests are welcome! Feel free to check issues page.

# License
Distributed under the MIT License. See LICENSE for more information.

# Contact
Saikiran Golla - saikiran.igsk@gmail.com
