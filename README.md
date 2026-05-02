# agent-injection-demo

# Indirect Prompt Injection — Demo
 
A proof-of-concept showing how malicious instructions hidden inside documents can hijack an LLM-based agent into executing unauthorised actions.
 
## Setup
 
```
pip install langchain langchain-ollama matplotlib
ollama pull llama3
ollama serve
```
 
## Run
 
Open `demo.ipynb` and run cells in order. Requires `normal.txt` and `poisoned.txt` in the same folder.
 
## What It Does
 
Tests four injection styles — None, Aggressive, Polite, Disguised — across 10 trials each and plots attack success rates.
 
