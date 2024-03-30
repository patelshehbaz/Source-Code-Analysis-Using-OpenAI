# Source-Code-Analysis-Using-OpenAI

This cutting-edge application is designed to empower developers by providing detailed explanations of GitHub repository code. Just provide a public link to a repo and ask any question in the chatbot interface - you'll get a comprehensive analysis, leveraging the powerful capabilities of OpenAI's GPT-3!

### How to run?

STEPS:

Clone the repository

```
Project repo: https://github.com/patelshehbaz/Source-Code-Analysis-Using-OpenAI.git
```

STEP 01- Create a conda environment after opening the repository

```
conda create -n venv python=3.8 -y
```

```
conda activate venv
```

STEP 02- install the requirements

```
pip install -r requirements.txt
```

Create a .env file in the root directory and add your OPENAI_API_KEY credentials as follows:

```
OPENAI_API_KEY = "xxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
```

```
python app.py
```

### Techstack Used:

- Python
- LangChain
- Flask
- OpenAI GPT 3.5
- ChoromaDB
