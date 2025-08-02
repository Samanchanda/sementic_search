 # 🔍 Semantic Search with HuggingFace Embeddings

This project demonstrates a simple and powerful semantic search system using Hugging Face language models and cosine similarity. It takes a query, encodes it along with a set of documents using transformer-based sentence embeddings, and returns the most semantically similar document.




🚀 Features

Sentence-level semantic understanding using embeddings

Query-to-document matching using cosine similarity

Supports HuggingFace Embeddings via langchain_huggingface

Simple and extensible codebase — ideal for educational use and prototyping





🧠 Model Used

Model: BAAI/bge-small-en-v1.5

Lightweight, high-performing embedding model

Provided by Hugging Face and integrated using langchain_huggingface





#🔧 Technologies

Python

Hugging Face Transformers

LangChain (Embedding layer)

Scikit-learn

NumPy

Google Colab / Jupyter Notebook

dotenv (for managing secrets)





📌 Example

query = "tell me about Peshawar"

Returns the document:

> "Peshawar is an ancient city known for its Pashtun heritage and traditional cuisine."



Similarity Score: 0.87+ (depending on the model version)



📁 How to Use

1. Install required packages:



pip install langchain-huggingface huggingface_hub python-dotenv sentence-transformers

2. Set your Hugging Face API Token via .env or Colab userdata


3. Run the notebook to test the similarity engine.





🔗 Notebook Link

🔗 View in Google Colab




🙌 Contributed by

Saman Tariq
AI Enthusiast | LegalTech Explorer | NLP Practitioner
