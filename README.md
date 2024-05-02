# LangChain-App-to-Chat-with-Multiple-PDFs

## Introduction
------------
The MultiPDF Chat App is a Python-based application designed to enable chatting with multiple PDF documents. This app allows you to pose questions in natural language about the content of the PDFs, and it uses a language model to generate pertinent answers to your inquiries. It's important to note that the app is limited to responding to questions that pertain to the PDF documents that have been loaded.

## How It Works
------------

![MultiPDF Chat App Diagram](/PDF-LangChain.jpg)

The application operates through the following steps to deliver answers to your inquiries:

1. PDF Loading: The app loads multiple PDF documents and extracts the textual content from them.
2. Text Chunking: The text obtained from the PDFs is segmented into smaller, manageable pieces.
3. Language Model: The app employs a language model to create vector representations (embeddings) of these text segments.
4. Similarity Matching: Upon receiving a question, the application compares it against these text segments to find the ones that are most semantically related.
5. Response Generation: The chosen segments are then processed by the language model, which crafts a response drawing from the pertinent sections of the PDFs.
