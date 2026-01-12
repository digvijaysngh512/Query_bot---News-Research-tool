
# Querybot: News Research Tool 

Querybot is a user-friendly news research tool designed for effortless information retrieval. Users can input article URLs and ask questions to receive relevant insights from the stock market and financial domain.


## Features

- Load URLs or upload text files containing URLs to fetch article content.
- Process article content through LangChain's UnstructuredURL Loader
- Construct an embedding vector using OpenAI's embeddings and leverage FAISS, a powerful similarity search library, to enable swift and effective retrieval of relevant information
- Interact with the LLM's (Chatgpt) by inputting queries and receiving answers along with source URLs.


## Installation


2.The web app will open in your browser.

- On the sidebar, you can input URLs directly.

- Initiate the data loading and processing by clicking "Process URLs."

- Observe the system as it performs text splitting, generates embedding vectors, and efficiently indexes them using FAISS.

- The embeddings will be stored and indexed using FAISS, enhancing retrieval speed.

- The FAISS index will be saved in a local file path in pickle format for future use.
- One can now ask a question and get the answer based on those news articles
- In video tutorial, we used following news articles
  - https://www.moneycontrol.com/news/business/tata-motors-mahindra-gain-certificates-for-production-linked-payouts-11281691.html
  - https://www.moneycontrol.com/news/business/tata-motors-launches-punch-icng-price-starts-at-rs-7-1-lakh-11098751.html
  - https://www.moneycontrol.com/news/business/stocks/buy-tata-motors-target-of-rs-743-kr-choksey-11080811.html

# Conclusion
Querybot – News Research Tool (GenAI / NLP / Product-Based AI) | Self Project

Built a Retrieval-Augmented Generation (RAG) system using LangChain, enabling question answering over financial news articles loaded via URL/text inputs and processed with UnstructuredURLLoader 

Implemented text chunking (1000 tokens, 200 overlap), OpenAI embeddings, and FAISS vector indexing for semantic similarity search, with embeddings persisted via pickle for fast reuse 

Integrated RetrievalQAWithSourcesChain with an LLM (ChatGPT/OpenAI) and a Streamlit UI, returning answers with source URLs for explainable news research workflows 
