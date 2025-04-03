First install the requirements file using below command.

```
pip install -r requirements.txt
```


Then paste your open-ai API key inside the .env file by first creating it with the variable  OPENAI_API_KEY.

Then run the file using :

```
streamlit run app.py
```

This chatbot first creates chunks of texts using the charactertext splitter using Langchain. Then creates the vector database using FAISS and then uses RAG techniques to answer the questions based on the pdf.
