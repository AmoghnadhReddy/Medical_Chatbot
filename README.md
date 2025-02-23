# Medical_Chatbot

## Steps to run:

Clone the Repo

### STEP 01- Create a conda environment after opening the repository

```bash
conda create -n medical_chatbot python=3.10 -y
```

```bash
conda activate medibot
```

### STEP 02- Install the requirements

```bash
pip install -r requirements.txt
```

### Create a `.env` file in the root directory and add your Pinecone & Huggingface credentials as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
HF_TOKEN = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```
