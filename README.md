# llm_engineering

This is a project from my learnings from various resources Online like https://github.com/ed-donner/llm_engineering and more.

1. Install Anaconda:

2. Set up the environment: Create the environment: `conda env create -f environment.yml` and then activate by using the command `conda activate llm_env`

3. Start Jupyter lab: `jupyter lab`

4. python -m pip install --upgrade pip and then do `pip install -r requirements.txt` which takes about a few mins to install all dependencies mentioned inside the requirements.txt file. 

5. Get Open AI's key from `https://platform.openai.com/api-keys` and create .env files and paste the key with a key `OPENAI_API_KEY=sk-proj-*`

### Ollama

Denefits of Ollama: No API charges - open-source and Data doesn't leave your box while its significantly less power than Frontier Models.

1. Install Ollama from ollama.com

2. install the models that you want to run `ollama run llama3.2` and then to start the server run `ollama serve`

3. verify if the ollama is running `http://localhost:11434/`
