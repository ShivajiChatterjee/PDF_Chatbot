# PDF-Indexing-and-QA

## Overview

This project demonstrates a workflow for extracting text from a PDF file, creating an index file, and interacting with the OpenAI GPT-3 model to answer user queries based on the indexed PDF information.

## Features

- PDF text extraction using PyMuPDF.
- Construction of an index file containing the extracted text.
- Interaction with the OpenAI GPT-3 model for question answering.

## Requirements

- Python 3.x
- Install required packages using:
  ```bash
  pip install llama-index==0.5.6
  pip install langchain==0.0.148
  pip install openai==0.28
  pip install PyMuPDF

# Workflow

## PDF Text Extraction:
The extract_text_from_pdf function uses PyMuPDF to extract text from a PDF file.

## Index Construction:
The construct_index function creates an index file containing the extracted text.

## Interacting with GPT-3:
The ask_ai function prompts the OpenAI GPT-3 model with user queries based on the indexed PDF information.

## User Interaction:
Users are prompted to input queries, and GPT-3 generates responses based on the information from the PDF.

## Configuration
Adjust max_context_length in the code to control the length of the context provided to the GPT-3 model.
Modify the GPT-3 parameters such as max_tokens, temperature, and stop according to your requirements.
