# Funny agile clock

This repo provides Python code for a Streamlit app which implements an 'agile clock' which e.g. can be used in meetings. The GenAI agent is based on Ollama and will 'chase' the speaker in a polite way to hurry up the more time passes by. For every session the app will select a new agent profile, whose 'dialect' it will adapt to remind the speaker on the remaining time. Code is based on Python 3.12.

# Setup

Create virtual environment with required packages 
```bash
python3 -m venv clock
source clock/bin/activate
```

```
pip install -r requirements.txt
```
