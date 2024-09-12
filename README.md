# Aerospace_Design_Allowables_LLM
Repo contains different methods of extraction of tabular data from design allowable tables.

Notebooks were run using Google Colab - free version


Instructions for running files

1) 01_RAG_Example
- This notebook contains an implementation of RAG using 2024 aluminum as knowledge base.
- The notebook contains library installation code. 
- An OpenAI api key is needed to run the code.
  
2) 02_Text_to_SQL and Semantic Search
- This notebook contains an implementation of text to SQL and semantic search.
- The notebook contains library installation code. 
- An OpenAI api key is needed to run the code.
- For vector storage of semantic data, I used pinecone.io. You need to create an account and obtain a API KEY to run this notebook. Creating an account is free
- If you choose to re-run the notebook after using pinecone, you first have to go into the pinecone website and delete the previously created index.
- Source = https://www.youtube.com/watch?v=ZIvcVJGtCrY&t=489s
- Source2 = https://docs.llamaindex.ai/en/stable/examples/index_structs/struct_indices/SQLIndexDemo/

3) 03_Advanced_RAG_Pnadas
- This notebook contains an implementation of advanced RAG on tabular data.
- The notebook contains library installation code.
- An OpenAI api key is needed to run the code.
- The notebook uses a .csv file as input. If ran on google colab, you need to upload the .csv file.
- Source = https://www.youtube.com/watch?v=L1o1VPVfbb0&t=674s
- Source2 = https://docs.llamaindex.ai/en/stable/examples/pipeline/query_pipeline_pandas/
- Source3 = https://www.youtube.com/watch?v=T0bgevj0vto


Pinecone = https://app.pinecone.io/organizations/-O4Ely1KM4y7nHmv00g_/projects/e56d9752-fe00-4618-88e6-3868fe8ebd95/indexes?sessionType=login&_gl=1*18fhy73*_up*MQ..&gclid=Cj0KCQjww5u2BhDeARIsALBuLnPKMdX_kSfiXi7uCSFD3X1p8lmrYTYXny-YKA3mN1ABQxBETv2MXyMaAhLgEALw_wcB
OpenAI API = https://openai.com/index/openai-api/


