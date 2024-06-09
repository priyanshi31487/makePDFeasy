# makePDFeasy
This project allows users to upload PDF files and interact with their content using natural language queries. It leverages Google Generative AI for embeddings and FAISS for similarity search to provide accurate answers from the PDF documents
# Features
Users can upload PDF files for content extraction and processing.
Extract text from PDFs and split it into manageable chunks using LangChain's RecursiveCharacterTextSplitter.
Create embeddings for text chunks using Google Generative AI.
Use FAISS to perform similarity searches on the embeddings for efficient information retrieval.
Users can input queries to receive detailed answers based on the uploaded PDF content.
Provide source context and references for the answers derived from the PDFs.

![image](https://github.com/priyanshi31487/makePDFeasy/assets/113574662/f1d7a1f9-f19d-4789-a1cd-5b13c27c1b52)

# Installation

1.Clone this repository to your local machine using:

  git clone https://github.com/priyanshi31487/makePDFeasy

2.Install the required dependencies using pip:

    pip install -r requirements.txt

3.Set up your Google API key by creating a .env file in the project root and adding your API

    GOOGLE_API_KEY=your_api_key_here
    
4. Run the Streamlit app by executing:

    streamlit run main.py

    
    

  
