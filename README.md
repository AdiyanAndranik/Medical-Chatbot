# Medical-Chatbot

# How to run?
### STEPS:

Clone the repository

```bash
Project repo: https://github.com/AdiyanAndranik/Medical-Chatbot.git
```

### STEP 01 - Create an environment after opening the repository

```bash
python -m venv venv
```
For windows
```bash
.\venv\Scripts\activate
```
For Linux or Mac
```bash
./source/bin/activate
```

### STEP 02 - Install all the requirements
```bash
pip install -r requirements.txt
```


### Create a `.env` file in the root directory and add your Pinecone credential as follows:

```ini
PINECONE_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```


### Download the quantize model from the link provided in model folder & keep the model in the model directory:

```ini
## Download the Llama2 Model:

llama-2-7b-chat.ggmlv3.q4_0.bin


## From the following link:
https://huggingface.co/TheBloke/Llama-2-7B-Chat-GGML/tree/main
```
