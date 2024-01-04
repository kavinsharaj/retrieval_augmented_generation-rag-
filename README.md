# RAG
- RAG is an AI framework for retrieving facts from an external knowledge base to ground large language models (LLMs) on the most accurate,
  up-to-date information and to give users insight into LLMs' generative process.

# ATS USING RAG
- Filter most suitable application or resume using retrieval augemented generation leveraging mistral-7b.

- # Requirements
 ```python
- !pip install -q transformers
- !CMAKE_ARGS="-DLLAMA_CUBLAS=on" FORCE_CMAKE=1 pip install  llama-cpp-python --no-cache-dir # remove args to work in cpu
- !pip install -q llama-index
- !pip -q install sentence-transformers
```
