# Book Recommendation System using LLM  

## Overview  
The **Book Recommendation System** leverages OpenAI's powerful language models to generate embeddings for textual representations of books. By utilizing these embeddings, the system efficiently stores and retrieves information about similar books using FAISS (Facebook AI Similarity Search). This allows users to input a book description or title and quickly find the top N similar entries based on their preferences, enhancing the book discovery process.  

## Features  
- Generate embeddings from textual representations using OpenAI's API.  
- Store embeddings in a FAISS index for fast retrieval.  
- Retrieve the top N similar entries based on a given input string.  

## Requirements  
- Python  
- `numpy`  
- `faiss` (Install using `faiss-cpu` or `faiss-gpu` based on your setup)  
- `openai`  
- `pandas`   
