# Simple RAG PDFChat App

## **Overview**

This app allows users to upload a PDF document and engage in a dynamic chat conversation with the Mistral Language Model using a simple implementation of the Retrieval Augmented Generation (RAG) technique. This app can running locally. 

## **Features**

- **PDF Interaction:** Users can easily upload a PDF document to the application.
- **Streamlit:** Used for building the interface, upload PDFs and interact with chat. Engage in natural language conversations with Mistral 7B.
- **Run it locally:** The app run locally

## **Requirements**

Make sure you have the following installed:

- Required libraries: **`langchain`**, **`streamlit`**, **`chromadb`**, **`fastembed`**, **`pypdf`**
- Ollama: you need to install **`ollama`** visit [ollama.ai](http://ollama.ai)
- Mistral 7B

## **Installation**

1. Clone the repository:
    
    ```bash
    git clone https://github.com/jacttp/simpleRAG.git
    ```
    
2. Install the required libraries:
    
    ```bash
    pip install -r requirements.txt
    ```
    
3. Download and set up Mistral language model according to the provided instructions.
    
    ```bash
    ollama pull mistral
    ```
    

## **Usage**

1. Run the Streamlit app:
    
    ```bash
    streamlit run app.py
    ```
    
2. Upload a PDF document and start chatting with Mistral.