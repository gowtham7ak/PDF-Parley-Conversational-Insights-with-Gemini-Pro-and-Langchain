# KITH 🦋 - PDF Conversational Analysis

![KITH Logo](link_to_kith_logo.png) <!-- Add an appropriate link to your KITH logo -->

## Overview

KITH 🦋 is a web application built with Streamlit for performing conversational analysis on PDF documents. It leverages Google Generative AI for embeddings and conversational interactions to answer user queries based on the content of uploaded PDF files.

## Features

- **PDF Processing:** Extracts text from uploaded PDF files.
- **Text Chunking:** Splits extracted text into manageable chunks.
- **Embedding and Vector Store:** Utilizes Google Generative AI Embeddings and FAISS for efficient storage and retrieval of text vectors.
- **Conversational Chain:** Sets up a conversational chain for question-answering based on user input.
- **User-Friendly Interface:** Built with Streamlit for an interactive and intuitive user experience.

## How to Use

1. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   
Configure Environment:

Create a virtual environment and activate it.
Set up environment variables, including the Google API key, in a .env file

python your_script_name.py

Usage:

Upload PDF files using the sidebar.
Ask questions related to the PDF content in the text input.
View the generated responses from the conversational chain.

Dependencies
Streamlit
PyPDF2
langchain
langchain_google_genai
google.generativeai
FAISS
dotenv
Configuration
Ensure you have a Google API key and set it in the .env file.
Customization
Customize the prompt template and models based on your specific use case.
Adjust the Streamlit layout and styling to fit your branding.
Contributing
Contributions are welcome! If you find a bug or have an enhancement in mind, please open an issue or submit a pull request.

License
This project is licensed under the MIT License.

Acknowledgments
Thanks to the contributors and the open-source community for their valuable contributions.
Streamlit for providing a seamless platform for building web apps with Python.
