# llms-rag
LLMs and RAG practical handson : DataTalksClub

## Environment setup from scratch
- Main reference (but then I did below changes) : https://github.com/DataTalksClub/llm-zoomcamp/blob/main/01-agentic-rag/lessons/02-environment.md
- Create a new public repo in github.
- I am using git bash (mingw for windows) instead of powershell or cmd prompt.
- create .gitignore
- create .venv using `python -m venv .venv` (for virtual environments) in git bash and .env file(for secrets/keys). Add them to .gitignore!!
- Activate in windows using `source .venv/Scripts/activate` in git bash and then start a vscode session using `code .`.
- I am installing packages using pip instead of uv. 
    - uv has an added advantage that a file similar to requirements.txt is autocreated and autofilled with dependencies. 
    - Also for uv, venv seems to be autocreated.
- Login to openai API website and create a project. In that project, add a secret key and add credits for using in this. 
- use dotenv for loading the env file (check lesson).

## Solve this :
- I had 2 pythons installed : one via anaconda and another via Microsoft store. I am using the conda one, so set the path variable to include C:/ProgramData/anaconda3 and C:/ProgramData/anaconda3/Scripts
- An environment file is configured but terminal environment injection is disabled. Enable "python.terminal.useEnvFile" to use environment variables from .env files in terminals.

