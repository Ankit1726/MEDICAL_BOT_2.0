# MEDICAL_BOT_2.0
Real Time ChatBot for solving Heatlhcare Illness related Problem working like as Personal Assitant Suggest medical Problem Solution


## Steps For Project Setup
### create conda environemnt
```bash
conda create -n medibot python=3.10 -y
```
### activate environment
```bash
conda activate medibot
```
### install requirements.txt
```bash
pip install -r requirements.txt
```

### Create a .env file in the root directory and add your Pinecone & Groq credentials as follows:
```bash
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
GROQ_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"

# run the following command to store embeddings to pinecone
python store_index.py

# Finally run the following command
python app.py
```

### Tech Stack 
- Techstack Used:
- Python
- LangChain
- Flask
- GPT
- Pinecone

#### Local PORT : http://127.0.0.1:8080
