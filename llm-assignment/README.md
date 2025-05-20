# Steps to run 
1. clone the directory in your local
2. create a venv in your environment
3. install all the dependences from requirements.txt
4. now you need to install ollama in your local system from https://ollama.com/
5. then pull and run commands  
    - ollama pull nomic-embed-text 
    - ollama pull mistral
    - olama serve
6. then goto your venv and run "python populate_database.py" to populate the database
7. Finally, run the command "python query_data.py "<QUESTION>"" to get the result
