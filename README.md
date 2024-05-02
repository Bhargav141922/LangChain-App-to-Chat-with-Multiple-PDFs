# LangChain-App-to-Chat-with-Multiple-PDFs

## Introduction
------------
The MultiPDF Chat App is a Python-based application designed to enable chatting with multiple PDF documents. This app allows you to pose questions in natural language about the content of the PDFs, and it uses a language model to generate pertinent answers to your inquiries. It's important to note that the app is limited to responding to questions that pertain to the PDF documents that have been loaded.

## How It Works
------------

![MultiPDF Chat App Diagram](/PDF-LangChain.jpg)

The application follows these steps to provide responses to your questions:

1. PDF Loading: The app reads multiple PDF documents and extracts their text content.

2. Text Chunking: The extracted text is divided into smaller chunks that can be processed effectively.

3. Language Model: The application utilizes a language model to generate vector representations (embeddings) of the text chunks.

4. Similarity Matching: When you ask a question, the app compares it with the text chunks and identifies the most semantically similar ones.

5. Response Generation: The selected chunks are passed to the language model, which generates a response based on the relevant content of the PDFs.
