# Funny agile clock

This repo provides Python code for a Streamlit app which runs an 'agile clock' which e.g. can be used in meetings. The GenAI agent is based on Ollama and will 'chase' the speaker in a polite way to hurry up the more time passes by. For every session the app will select a new agent profile, whose 'dialect' it will adapt. Code is based on Python 3.12.

# Setup

Create virtual environment with required packages 
```bash
python3 -m venv clock
source clock/bin/activate
```

```
pip install -r requirements.txt
```

Download the Ollama server from https://ollama.com

Current available agent profiles (feel free to add your own;)
```
Cowboy: 🤠
Pirate: 🏴‍☠️
Hip-hop singer: 🎤
Insurance employee: 💼
Rastafarian: 🧑🏾‍🦱
Alien from another planet: 👽
Vogon Poet from Hitchiker's guide to the galaxy: 4️⃣2️⃣
Existentialist Philosopher: 🤔
William Shakespeare: 🎭
Master Yoda: 🧙‍♂️
```
