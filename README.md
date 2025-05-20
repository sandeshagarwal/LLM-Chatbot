Steps to run
clone the directory in your local
create a venv in your environment
install all the dependences from requirements.txt
now you need to install ollama in your local system from https://ollama.com/
then pull and run commands
ollama pull nomic-embed-text
ollama pull mistral
olama serve
then goto your venv and run "python populate_database.py" to populate the database
Finally, run the command "python query_data.py """ to get the result
