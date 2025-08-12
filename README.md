# RAG pipeline using LangChain

A simple retrieval-augmented generation framework using LangChain.

For embeddings, I use the **all-mpnet-base-v2** model from HuggingFace.
For the knowledge base I use Chromadb, which is a vector management library. It is light weight and an easy alternative for vector databases (for small prototyping or dev projects).
For the LLM, I use **declare-lab/flan-alpaca-large*** from HuggingFace.


To run:

1. Install requirements using <br>
`pip install -r requirements.txt`

2. Create your knoweldge base by adding pdfs to the data folder. <br>

3. Run the code using <br>
`python RAG.py`



