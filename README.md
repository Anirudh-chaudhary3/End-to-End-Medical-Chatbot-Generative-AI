# End-to-End-Medical-Chatbot-Generative-AI


# How to run?
### STEPS :

Clone the repository

```bash
Project repo: https://github.com/
```

### STEP 1 : Create a conda environment after opening the repository

```bash
conda create -n medibot python=3.10 -y
```

```bash
conda activate medibot
```


### STEP 2 : Install the requirements

```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your Pinecone & Openai credentials as follows:

```ini
PINECONE_API_KEY = "XXXXXXXXXXXXXXXXXXXXXXXXXXXXX"
OPENAI_API_KEY = "XXXXXXXXXXXXXXXXXXXXXXXXXXXXX"
```

```bash
# Run the following command to store embeddings to Pinecone
python store_index.py
```

```bash
# Finally run the following command
python app.py
```

# Now,
```bash
open up localhost:
```

### Techstack Used :

- Python
- LangChain
- Flask
- COHERE
- Pinecone