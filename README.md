# Gitpod - Replit - Template: Jupyter

A lean template to run Jupyter Notebook or Lab locally / in Gitpod / in Replit.

## Run in Gitpod
https://gitpod.io/#https://github.com/aknip/Gitpod-Replit-Template_Jupyter

In Gitpod Jupyter is supported out-of-the-box: Just open a .ipynb file 

## Virtual environment using uv
- Install: curl -LsSf https://astral.sh/uv/install.sh | sh
- Create a virtual environment in current dir in folder .venv.
	- `uv venv`
- Activate environment
	- `source .venv/bin/activate`
- Deactivate environment
	- `deactivate`

uv pip install notebook==7.2.2 jupyterlab==4.2.5 openai==1.42.0 langchain==0.2.14 python-docx==1.1.2 pypandoc-binary==1.13


## Install dependencies

uv pip install -r requirements.txt


# Start Jupyter

jupyter notebook
jupyter lab