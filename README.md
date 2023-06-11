# chat with multiple docs in pdf format
  
  This repo has working code for LLM based chatbot for chatting with your own document. 
  
  ## Process
  Upload your pdf -> Ingest and store data into vectorstore by chunking and Embeddings -> Ask question to chatbot 
  -> question transformed into embeddings -> Semantic search from vectorstore -> Return high rank results 
  
  ## Framework used
  * [Langchain](https://python.langchain.com/en/latest/index.html)
  * [Streamlit](https://streamlit.io/)

  ## Large Language Model available
  * GPT 3.5 Turbo
  * [Instruct](https://huggingface.co/google/flan-t5-xxl) 
  
  ## For Embedding
  * [OpenAI Embeddings](https://platform.openai.com/docs/guides/embeddings)
  * [Instruct Embeddings](https://instructor-embedding.github.io/)
