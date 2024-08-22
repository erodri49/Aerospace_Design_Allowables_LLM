# Aerospace_Design_Allowables_LLM
Repo contains different methods of extraction of tabular data from design allowable tables.

Notebooks were run using Google Colab - free version


Instructions for running files

1) 01_RAG_Example
- This notebook contains an implementation of RAG using 2024 aluminum as knowledge base.
- The notebook contains library installation code. 
- An OpenAI api key is needed to run the code.
  
3) 02_Text_to_SQL
- This notebook contains an implementation of text to SQL and semantic search.
- The notebook contains library installation code. 
- An OpenAI api key is needed to run the code.
- For vector storage of semantic data, I used pinecone.io. You need to create an account and obtain a KEY to run this notebook. Creating an account is free

5) 03_Advanced_RAG_Pnadas
- This notebook contains an implementation of advanced RAG on tabular data.
- The notebook contains library installation code.
- An OpenAI api key is needed to run the code.
- The notebook uses a .csv file as input. If ran on google colab, you need to upload the .csv file.
